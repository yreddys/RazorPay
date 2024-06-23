Since the remote origin is pointing to an incorrect URL, you can remove it and add the correct remote URL. Here are the steps:

### 1. Remove the Existing Remote
Remove the incorrect remote origin:

```sh
git remote remove origin
```

### 2. Add the Correct Remote
Add the correct remote URL for your repository:

```sh
git remote add origin https://github.com/yreddys/payment.git
```

### 3. Push Your Changes
Push your changes to the newly added remote repository:

```sh
git push -u origin main
```

### Full Commands Combined
Here are all the commands you need to run:

```sh
git remote remove origin
git remote add origin https://github.com/yreddys/payment.git
git push -u origin main
```

By following these steps, you should be able to successfully update the remote URL and push your changes to the correct repository.
