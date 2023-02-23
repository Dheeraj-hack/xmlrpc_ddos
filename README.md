# xmlrpc_ddos

#This code is a proof of concept exploit for a Denial of Service vulnerability in WordPress and Drupal XML-RPC endpoints, and should not be used for malicious purposes. Running this code against a live website without permission is illegal and can cause significant harm to the target system and its users.

That being said, if you want to experiment with this code on your own local environment for educational purposes, you can follow these steps:

1. Open a text editor and copy the Python 3 code into a new file.

2. Modify the req variable to point to a valid XML-RPC endpoint on your local environment. For example, you can use the following URL to test against a local WordPress   installation:
req = urllib.request.Request('http://localhost/wordpress/xmlrpc.php', data.encode('utf-8'))

3. Save the file with a .py extension, such as xmlrpc_dos.py.

4. Open a terminal or command prompt and navigate to the directory where you saved the file.

5. Run the script using the Python interpreter. For example, you can use the following command to run the script:
python xmlrpc_dos.py

This will start the script and create multiple threads that send the specially crafted XML payload to the target endpoint.

You should monitor your local environment while the script is running to ensure that it doesn't cause any unintended side effects, such as excessive CPU or memory usage.

Again, please use this code responsibly and only for educational purposes. Do not use it against live websites without permission

