# LabVIEW-communication-with-Atlas-Copco-controller-by-Using-Serial-Communication
LabVIEW communication with Atlas Copco controller by Using Serial Communication referring open Atlas's protocol.

Since I am trying to get a detailed of of tightening result to logging into LabVIEW. I fould one document that guild to communicate with Atlas copco controller you can find more detalied as an attached document.

The way to communication with this controller by using Serial communication are 2 kind of serial protocal.
- Serial ASCII protocol.
- Serial ASCII protocol with 3964R handshake 

Refered an attached document, we need to open serial port for communication first(Once we send message to open the port will be opening only 15second for your access) which mean you need to send a command to access within 15 minutes.
While the port is open we can send command to communicate with controller. After we get a talked back message, we can send a command to close protocal.

In this example, I also attached LabVIEW project that inclued by VIs following the detalied below:
- LabVIEW code for open port.
- LabVIEW code for access and get a worked result.
- LabVIEW code for close port.

You can specify what is the value that you would like to get by using "String subset" in LabVIEW and you can also adjust offset and lenght of string to get your wanted value.
The table in page 136 will help you about data selecting, and config Sting subset at offset and lenght.

PS. Please make sure that you open port before you are tightening.

if you have any comment, please drop me your comment. Thank you.
