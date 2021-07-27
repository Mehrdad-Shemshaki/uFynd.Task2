Task 2: Reporting

IDE & Development tools:

	.NET 4
	Visual studio 2010
	NUnit
	Visual Nunit
	Moq
	Newtonsoft.Json

HOW TO EXECUTE

Go to '\uFynd.Task2\uFynd.Task2\bin\Debug' and run 'uFynd.Task2.exe'.
In successful execution an excel file is created in the current path.

to run tests use Visual Nunit.


Optional: Suggest an architecture on how to automate the process that an
email is sent at time x attaching the report (frameworks, libraries, ready made
solutions etc.: free of choice).

An asynchronous message passing system based on message queueing tools like RabbitMQ is suggested. The proposed system 
frequently Check if there is any ready-to-send message is in queue. Then if exists, pop it from queue and
send the email with the attachment. It is essential for message sender systems to push their message in the queue.


 