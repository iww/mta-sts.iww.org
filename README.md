# MTA-STS policy for iww.org

Read about *SMTP Message Transfer Agent Strict Transport Security (MTA-STS)* in [RFC 8461](https://tools.ietf.org/html/rfc8461).

Each time this record is updated (for example, to change the mode from `testing` to `enforce`), the **_mta-sts** TXT record's ID attribute must be udpated. Set the ID to the current **UNIX Epoch time** including seconds (13 characters total). To quickly retrieve this value using JavaScript, execute `new Date().getTime();`.
