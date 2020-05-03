This Script will run the Edge DNS API for all the zones provided in the input, filter all CNAME recoirds associated with the zone and also run the GET request on those records if those records a CNAMED to Akamai.

Input would be:
1. Credentials in .edgerc under [dns] section
2. Account Switch Key for the account in line 31 of the run.py(need to add the value before running the script)
3. Zone names in input.xlsx file(sample file in the repo.download and edit this xlsx file), Sheet 1 to be populated with zone names, one per line
