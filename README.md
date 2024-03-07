# Airtel patterns test
~ This binary aims to test Airtel MSISDN Ranges (See bellow link).
	https://www.dignited.com/57218/safaricom-introduces-new-prefix-numbers-0110-and-0111/

# Requirements:
- Download or install java 21 on your workstation
- Download this binary AirtelPattern.jar

# Running the binary:
- To run the binary navigate to its directory and run bellow command

	java -jar AirtelPattern.jar 0778224569 0768224569 0714224569

The numbers can be more or less. 

# Sample Results
$ java -jar AirtelPattern.jar 0778224569
	- 0778224569 does not match Airtel MSISDN pattern

$ java -jar AirtelPattern.jar 0768224569
	- 0768224569 matches Airtel MSISDN pattern
