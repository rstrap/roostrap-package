NEEDED ASSETS:

installer which installs program in:

installer-script:

/data/data/com.termux/files/rootstrap/install-scripts/${program_name}/install.sh

uninstaller:

/data/data/com.termux/files/rootstrap/install-scripts/${program_name}/uninstall.sh

program files:

/data/data/com.termux/files/rootstrap/programs/{choose from 3rdparty, official, terminal or other}/${program_name}/

# warrant:

official - FOR BASEUTILS OR APPROVED AS OFFICIAL

3rdparty - non baseutils but a community package submitted through pull request

terminal - cli program

other - non community package but developer package (these can be without pull request)
