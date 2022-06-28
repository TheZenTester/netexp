# README.md
Tool to act as a repository for all of my shortcuts and notes.  This project is in its infancy, but for now the idea is to migrate the data I have in Joplin (shoutout to @tjnull for https://github.com/tjnull/TJ-JPT), but have tailored based on developing my methodologies over time.  This tool might not be for you right out of the box, but hopefully will give you a framework in which you can make it your own by forking and copypasta-ing your own commands you use most. For an already finished solution, check out @mike-hacks' tool [mxhelp](https://github.com/mikes-hacks/mxhelp), which was my inspiration for starting this project.

# Enhancements
- Have a command to run which will print out shortcuts for various stages of network pentest
- Have output print out in markdown format (i.e. glow , batcat)

# Syntax
`netexp [step] [sub-step]`

## Steps/Sub-step
As of now, this list is from TJ Null's TJ-JPT file
1. Recon
- General Checklist
	- tcpdump
	- network scanning
	- nmap
		- Speedy Nmap Scan
		- Nmap Scans
		- Specific Service Nmap
	- DNS Recon
	- Dig
	- Sublist3r (subdomain enum)
	- OWASP amass
2. Enumeration
3. Explotation
4. Post Exploitation
5. High Value Information
- Hashes
	- Dumping Hashes
	- Identifying Hash Types
	- Cracking Hashes Online - medusa, hydra
	- Cracking HAshes Offline- Wordlists, Hashcat, JTR, Wifi
