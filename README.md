# finance_admin

## A background Management of [finance_web](https://github.com/chowchunlok/finance_web/tree/master)

> ### Introduction:
>
> A admin built by Vue with Permission control & Token Authentication
>
> ### Skill
>
> Vue + Express + Mongoose

## Build Setup

```bash
# Clone project
git clone git@github.com:chowchunlok/finance_admin.git

# Install dependencies
npm install

# Serve with hot reload at localhost:9000
npm run dev

# Build for production with minification
npm run build

```

## Main Function

1. Log In/Log Out, every page needs valid token

![log in](./gif/login.gif)

2. Permission Control

- Different Roles can read different pages (admin role has register page but editor role)

![premission control](./gif/permission.gif)

3. Edit Article

![edit article](./gif/edit.gif)

4. Check User

![user](./gif/user.png)
