Readme: the SCHEDULE PREVIEWER project.

Note: This is part of the SCHEDULE PREVIEWER project.

SCHEDULE PREVIEWER is an Excel 2016 file designed to parse schedule data and connect it to
	* patient accounts receivable so the billing office can communicate efficiently to the reception desk.
	* Each day's appointments are sent to a printable output screen that operates as a tickler, indicating
	* various statuses that the front desk can follow up on. Statuses include:
		* patients with no known insurance: please verify coverage
		* patients with expired insurance: please get new scanned card
		* patients with expired ID: please get new scan of ID
		* patients who are pre-paid: reminder, do not collect co-pay
		* patients who have a balance due: reminder, contact the billing desk
		* patients who are flagged as "bad address on file": obtain new mailing address
		* patients who are flagged as "sent to collections": reminder, contact the billing office
	* Patients who do not have ANY flags are treated as default (ie, collect co-pay = YES)