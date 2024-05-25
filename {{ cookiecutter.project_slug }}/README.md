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

## Import

Importing data from various sources, such as your bank or credit card accounts, is one major pain point of using plain-text accounting books like Beancount.
We made it easier than ever for you to import various sources with rule-based automation.
We have already provided you a sample import rules file at [.beanhub/imports.yaml](/repos/{{ cookiecutter.username }}/{{ cookiecutter.project_slug }}/blob/master/.beanhub/imports.yaml) in this repository.


You can download this [sample CSV file here](https://github.com/LaunchPlatform/beanhub-import-demo/blob/fb81e4a03b81fe9d40a58a51a25d82a9560cfeeb/import-data/mercury/2024.csv).
To upload and import it, click the **Import** button on the left-hand side menu and then click **Upload Files**.
Or you can [click here](/repos/{{ cookiecutter.username }}/{{ cookiecutter.project_slug }}/import/upload-files/master).

TODO:

Then, choose the CSV file you downloaded and press the upload button.
After that, you will need to review the uploaded file.
Press the **Import** button, and here you go!

TODO:

You just imported transactions from the bank account CSV file with a few clicks!
Please read our blog article [FIXME](https://beanhub.io/blog/2023/07/31/automating-beancount-data-input-with-beanhub-custom-forms/) to learn more about it.

<a href="https://beanhub.io/blog/2023/07/31/automating-beancount-data-input-with-beanhub-custom-forms/">
    <img src="http://beanhub.io/blog/2023/07/31/automating-beancount-data-input-with-beanhub-custom-forms/cover.png" style="max-width: 600px">
</a>

## Forms

Input repetitive transactions manually are time-consuming and error-prone.
BeanHub allows you to define your custom forms for generating transactions.
We have already provided a sample form for you in the [.beanhub/forms.yaml file](/repos/{{ cookiecutter.username }}/{{ cookiecutter.project_slug }}/blob/master/.beanhub/forms.yaml).
You can try it out by clicking the **Forms** button on the left-hand side menu, then clicking the form **Hours spent on XYZ contracting project**, or simply [clicking here](/repos/{{ cookiecutter.username }}/{{ cookiecutter.project_slug }}/form/add-xyz-hours).

<img src="https://github.com/LaunchPlatform/beanhub-beancount-cookiecutter/blob/49a7a7924a7e5649d829fcedfdbeb2814927ac87/assets/beanhub-form-screenshot.png?raw=true" style="max-width: 600px">

After you submit the form, a new transaction will be added in a Git commit based on your input.

<img src="https://github.com/LaunchPlatform/beanhub-beancount-cookiecutter/blob/49a7a7924a7e5649d829fcedfdbeb2814927ac87/assets/beanhub-form-git-diff.png?raw=true" style="max-width: 600px">

Please read our blog article [Automating Beancount data input with custom forms makes your life 10 times easier!](https://beanhub.io/blog/2023/07/31/automating-beancount-data-input-with-beanhub-custom-forms/) to learn more about it.

<a href="https://beanhub.io/blog/2023/07/31/automating-beancount-data-input-with-beanhub-custom-forms/">
    <img src="http://beanhub.io/blog/2023/07/31/automating-beancount-data-input-with-beanhub-custom-forms/cover.png" style="max-width: 600px">
</a>


## API Access

Have you ever wondered how cool it would be if you could read and write your Beancount accounting book with a well-defined API?
You are in luck.
BeanHub provides a featureful API that allows you to access your accounting books.
With this API, you can insert, update, or delete entries programmatically.
You can read the [API documents here](https://api.beanhub.io/redoc).
To access the API, you need to create an access token on the access token management page here.

Please read our blog article [New API access feature for reading and writing Beancount data easily](https://beanhub.io/blog/2023/08/28/announcement-of-the-new-api-feature/) to learn more about it.

<a href="https://beanhub.io/blog/2023/08/28/announcement-of-the-new-api-feature/">
    <img src="https://beanhub.io/blog/2023/08/28/announcement-of-the-new-api-feature/cover.png" style="max-width: 600px">
</a>

## Basic operations

In addition to the powerful custom form and import data feature, we also provide basic Beancount operations, such as adding new transactions.
You can also rename your account with a simple click.
More new features are coming soon:

- Modify entry
- Delete entry
- Split account

## Finally

Hope you find BeanHub useful.
We are working hard to add more features.
If you have any questions about BeanHub or suggestions, please don't hesitate to contact us at [support@beanhub.io](mailto:support@beanhub.io).
