starttls-email-check
====================

StartTLS email check

This is a bash script to see if your ISP is stripping/mangling your STARTTLS section of your emails. Some Desktop email clients like Thunderbird generally send outbound email on a TLS-wrapped port, like 587, and do not rely on STARTTLS, But there are some exceptions. Also note that some ISP's block port 25.
