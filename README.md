# MyPacketSniffer

Java command-line application to sniff network packets.
The filter is set to:
  -   protocol=TCP

# Compilation

```bash
gradlew buildSniffer
```

# Execution


```bash
java -jar build/libs/uk-all-1.0-SNAPSHOT.jar
```
The application will show you all available devices. You have to enter a number to choose which device you want to monitor.
It will then build a out.pcap with the captured packets and print on the terminal details of the packets.

# Example file

An example file out.pcap is in the root of the repository, it contains 10 TCP packets and can be open by Wireshark.

# Contributors
----
- [Lucas Benkemoun](https://github.com/LeBenki) (Student id:19909316)

