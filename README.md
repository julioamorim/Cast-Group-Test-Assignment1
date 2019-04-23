#Assignment Java Cast Group

#Goal
The goal of this assignment is to show your coding skills and what you value in software engineering. We belive that a good code is a well tested code, feel free to improve/add/extend.
=================================================
The assignment
==


•	Provide 2 http endpoints that accepts JSON base64 encoded binary data on both endpoints
o	<host>/v1/diff<ID>/left and <host>/v1/diff/<ID>/right
•	The provided data needs to be diff-ed and the results shall be available on a third endpont.
•	The results shall provide the following info in JSON format
o	If equal return true
o	If not equals but size different, return just size
o	If same size provide insight in where the diffs are, actual diffs are not needed
	Mainly offsets + length in the data
Must have
•	Solution written in Java
•	Internal logic shall be under unit test
•	Functionality shall be under integration test
•	Documentation in code
•	Clear and a good read-me.
