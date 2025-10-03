# Submitting a form to the same page

## If you are using Codespaces

- Open your existing codespace (you shouldn't create a new one) https://github.com/codespaces.
- In the terminal enter

```
git clone https://github.com/CIT2202/postback-forms
```

This will copy the contents of this repository into your codespace.
- If needed, start Apache i.e. enter `apache2ctl start` in the terminal

Now move onto [Completing the practical work](#practical)

## If you are using XAMPP

- Download the code in this repository (click on the big green button that says 'code')
- Unzip the folder.
- Copy it into the htdocs folder on XAMPP
- Open the folder using your text editor of choice e.g. VS Code

Now move onto [Completing the practical work](#practical)

## Completing the practical work <a name="practical"></a>
* Open *postback.php* in an code editor and view it through a browser (it must be on a server).
* Enter something for the email address and hit submit. The page should reload, and you should get a 'Valid form' message.
* Now try submitting the form without entering anything into the email field. You should get an error message.
* Have a good look at the code in *postback.php* and make sure you understand how this is working.  
* Add some more code to *postback.php* to test that the user has completed the _fullname_ text field.
* Notice how if we enter an email address, the email text field is re-populated with this value. Do the same for the fullname field.
* use these [notes](https://github.com/CIT2202/postback-forms/blob/master/postback-forms.md) to help you complete the exercises.
