## I'm having trouble... committing.

You're seeing some sort of error or message when you try to run the `git commit` command.

---

#### Nothing to commit

**Example error:**

```
$ git commit
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
```

**Solution:**

Nothing! You're done. This message means that you have no local changes - so either you've committed all your local changes, or you've lost work (in which case [go here](lost_work.md)). Either way, there's nothing to do here.

---

#### No email or name set

**Example error:**

```
$ git commit

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.
```

**Solution:**

Set your name and email on your local machine like so:

```sh
$ git config --global user.name YOUR_NAME
$ git config --global user.email YOUR_EMAIL
```

---

[Back to Main List](../../..)
