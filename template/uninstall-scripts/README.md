echo uninstalling ${program_name}...

rm -rf /data/data/com.termux/files/rootstrap/programs/${program_name}/

rm -rf /data/data/com.termux/files/rootstrap/install-scripts/${program_name}.sh

echo uninstalled ${program_name}

rm -rf /data/data/com.termux/files/rootstrap/uninstall-scripts/${program_name}.sh
