# {{ cookiecutter.project_slug }}

Hi there! 😄👋

Thank you for using BeanHub, and congratulations on creating your first BeanHub repository.
There are many things you can do with BeanHub.

## Getting started

First, to clone your repository locally, you can create an access token set with proper Git operation permissions on the [access token management page](https://app.beanhub.io/access-tokens).
Next, You can clone your repository locally by running:

```bash
git clone https://app.beanhub.io/repos/{{ cookiecutter.username }}/{{ cookiecutter.project_slug }}.git
```

The username is `{{ cookiecutter.username }}` as your BeanHub account, and the password should be the access token's secret key value.

You can modify your accounting book locally, commit and push it to BeanHub. See what happens:

```bash
git push
```

After you push your changes to BeanHub, you can refresh the web pages of your BeanHub repository to see the up-to-date accounting book data.
BeanHub is more than just a hosted Beancount based on Git.
Let's see what else you can achieve with it!

## Forms

Input repetitive transactions manually are time-consuming and error-prone.
BeanHub allows you to define your custom forms for generating transactions.
You can try it out by clicking the **Forms** button on the left-hand side menu, then clicking the form **Hours spent on XYZ contracting project**, or simply [clicking here](/repos/{{ cookiecutter.username }}/{{ cookiecutter.project_slug }}/form/add-xyz-hours).

TODO: insert form screenshot

After you submit the form, a new transaction will be inserted based on your input.

TODO:

Please read our blog article [Automating Beancount data input with custom forms makes your life 10 times easier!](https://beanhub.io/blog/2023/07/31/automating-beancount-data-input-with-beanhub-custom-forms/) to learn more about it.

<a href="https://beanhub.io/blog/2023/07/31/automating-beancount-data-input-with-beanhub-custom-forms/">
    <img src="http://beanhub.io/blog/2023/07/31/automating-beancount-data-input-with-beanhub-custom-forms/cover.png" style="max-width: 300px;">
</a>

## Import

Importing data from various sources, such as your bank or credit accounts, is one major pain point of using plain-text accounting books like Beancount.
We made it easier than ever for you to import various sources with rule-based automation.
You can download this sample CSV file by clicking the **Import** button on the left-hand side menu and then clicking **Upload Files.**

TODO:

Then click **Upload file** and choose the CSV file you just downloaded then upload.
After that, you will be asked to review the uploaded file.
Press the **Import** button, and here you go!

TODO:

You just imported more transactions from the bank account CSV file with a few clicks!
Please read our blog article to learn more about it.
