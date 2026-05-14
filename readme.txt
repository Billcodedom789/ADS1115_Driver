readme
Driver: ads1115_driver  

Commands to Use
-----------------------
make install_driver      # Install the module to the system
make uninstall_driver    # Uninstall the kernel module
make create_overlay      # Compile and copy the device tree overlay
make enable_overlay      # Add overlay to /boot/config.txt
make remove_overlay      # Remove the overlay
make end_reboot          # Reboot the system (after overlay or module changes)
make test                # Test overlay creation and activation

How to Load the Driver  
-----------------------
make create_overlay      # Compile and copy the device tree overlay
make enable_overlay      # Add overlay to /boot/config.txt
make install_driver      # Install the module to the system
make end_reboot          # Reboot the system to apply changes
