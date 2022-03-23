Use imapsync (https://imapsync.lamiral.info/) to transfer mail from Google to another IMAP server.


Usage:

copy file `env.example` to `.env` and insert the usernames, passwords and the second IMAP host.

Then run `# docker-compose up` This will run the container and output the results.

After that run `# docker-compose down` to remove it.



The `logs` folder contains the logs so you can look at what happened.


You can run this multiple times with no ill effect, except deleted messages on the new host will reappear.



