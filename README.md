# Instruction

Please read and follow the instruction.
## 1.Clone the project into your local PC.

When you want to clone, first select the folder that you want to place your project.

```bash
git clone https://github.com/rithnhel/gitTraining2019.git
```

## 2.Config Global USER and EMAIL

Global user. you have to put your name into ""
Ex: "Rith NHEL"

```bash
git config --global user.name "Your Name"
```

Global email. You have to put your email address that you create github account into ""
Ex: "parongnhel@gmail.com"

```bash
git config --global user.email "Your Email"
```
## 3.Add remote to local repository

```bash
git remote add origin https://github.com/rithnhel/gitTraining2019.git
```

## 4.Create a Brand
Create the new brand for your own work. You have to put the name of your brand by yourself.
Ex: RITH

```bash
git checkout -b yourbrandname
```

## 5.How to push your work file or directory into github repository

Check status of your work like how many file have you been change or create or delete.
```bash
git status
```

Add all change into your brand

```bash
git add .
```

Save all change into your brand. You have to put the commit message by yourself. And the commit message is represent about your work.
Ex: "Implement login feature with PHP"

```bash
git commit -m "commit message"
```
## 6.Pull and Push

Pull new work from the github repository

```bash
git pull --rebase origin master
```

Push your work from to github repository. For yourbrandname you have to put the brand that you are working for.
Ex: RITH

```bash
git push origin yourbrandname
```

Note: If you have never push or pull anything to github repository, then it will alert you the form loging while you rund the command to pull or push. so you have just to fill in your username and password that you log in to github into that form.

## 7.License
[Rith NHEL](https://github.com/rithnhel/)