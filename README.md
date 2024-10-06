# Terraboot Bootcamp Exampro

## Writing Good documentation - Using Codeblocks

Use codeblocks in *markdown* to allow users to copy and paste share code.

Allows copy and paste to replicate or research.

Three backticks (```) are used to display a code block

```

# Import the Active Directory module

Import-Module ActiveDirectory

# Set the username and new email address
$username = "jdoe"
$newEmail = "jdoe@example.com"

# Update the user's email address
Set-ADUser -Identity $username -EmailAddress $newEmail

# Confirm the change
Get-ADUser -Identity $username -Properties EmailAddress | Select-Object Name, EmailAddress
```

![nameofimage](https://www.gumtree.com/assets/frontend/latest_jobs_2.b05155d69e733cab888d04e884bbe94d.png)
