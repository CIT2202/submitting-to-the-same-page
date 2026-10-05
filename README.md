# Submitting a form to the same page

- Open your existing codespace (you shouldn't create a new one) https://github.com/codespaces.
- In the terminal enter

```
git clone https://github.com/CIT2202/submitting-to-the-same-page
```

In your Codespace, in VS Code, open the file _index.php_ and view it through a browser.

Enter something for the email address and hit submit. The page should reload, and you should get a 'Valid form' message.

Now try submitting the form without entering anything into the email field. You should get an error message.

Have a good look at the code in *index.php* and make sure you understand how this is working.  

Add some more code to *index.php* that will test if the user has completed the `fullname` text field.

Notice how if we enter an email address, the email text field is re-populated with this value. 

Do the same for the `fullname` field.

If you can get this to work, can you do a simple test to see if the user has entered an email address e.g. check for the presence of the '@' symbol. 

Use these [notes](submitting_to-the-same-page.md) to help you complete the exercises.
