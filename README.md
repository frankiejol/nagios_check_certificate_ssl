# nagios_check_certificate_ssl
Nagios check for ssl certificate validation

## Description

This is a check for any Nagios compliant monitorization tool to check
SSL certificates. It must be run in the local server using NRPE or similar
check plugins.

## Install

### Requirements

This nagios check requires Perl and some modules. This is the debian and derivates
installation guide, other distributions should be similar:

   `sudo apt install libdatetime-format-dateparse-perl libdatetime libdate-calc-perl libipc-run3-perl`

### Check file

Copy the file to a nagios plugins directory like /usr/lib/nagios/plugins

   `sudo cp check_certificate_ssl /usr/lib/nagios/plugins`

