# postgresql Install

1. First update brew before installing anything new. In terminal type:
```
brew update
```

2. Then use brew to install postgres:
```
brew install postgres
```

3. Start the postgres database server using:
```
brew services start postgresql
```

4. Create your first database named after your user with the following command:
```
createdb $USER
```

5. Test that your install worked by entering the psql shell:
```
psql
```

6. The above command will change your prompt to have a `#` in it. This just indicates you are inside the psql shell meaning you can interact with your databases.

  To exit the psql shell type:
```
\q
```

---

## Install Postico

You can download it here: [https://eggerapps.at/postico/](https://eggerapps.at/postico/)

Or via brew in the terminal:

```
brew install postico
```

Once you install it, open it and click `connect`. This will create a connection to your postgres database server, so you can interact with postgres via postico.

---

## Start / Stop Server

1. Start - `` brew services start postgresql ``
2. Stop - `` brew services stop postgresql ``
3. Check if running - `` brew services list ``
