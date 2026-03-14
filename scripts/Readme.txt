CASIRI Commissioning Document

Weather Station

1. Open a terminal and run:
./sparkplug_ws.sh (This step will prompt for the password: casiri123.)
The terminal will remain active, listening for the messages being transmitted.

To visualize the data, open a web browser such as Mozilla Firefox and navigate to the following URL:
http://localhost:8088/data/perspective/client/CASIRI

Once the graphical interface loads, click Sign in and use the following credentials:

Username: admin
Password: password

Camera

1. Open a terminal and run:
./jetson_ssh.sh
It will request the PC password (casiri123).
After that, it will prompt for the Jetson password: radio.
At this point, you will be connected to the Jetson via SSH.

2. Once inside the Jetson, run:
ps -A | grep indiserver (This command will return the indiserver process ID)

Then execute:
kill <previous_process_id> (Replace <previous_process_id> with the process number returned by the previous command)
./indiserver.sh (The terminal will remain occupied displaying the indiserver process status)

3. Without closing the previous terminal, open a new terminal, repeat Step 1 to access the Jetson, and run:
./sparkplug.sh (The terminal will remain listening to the messages being transmitted.)

4. Without closing the previous terminal, repeat Step 1 again to access the Jetson and run:
./captura.sh (The terminal will remain occupied performing image capture.)

With these steps completed, the data can be visualized through the graphical interface.
