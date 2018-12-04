# Automation suite for Inmarsat GX Pulse

 - Test case location: http://52.214.138.227:8080/qcbin/start_a.jsp
 - Domain: Demo
 - Project: GXAutomation

To run this test suite, your test environment must be connected to the Inmarsat network.

### VPN details

 - VPN client: FortiClient
 - VPN Type: SSL-VPN
 - Remote Gateway: 192.168.105.3
 - Custom port: n/a
 - Client certificate: None
 - Authentication: Save login
 - Username: InFuse
 - (Check 'Do not Warn Invalid Server Certificate')

### Usage

Execute in the project root using Maven: mvn test
