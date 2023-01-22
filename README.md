# erl-csurf

### Install

```
npm install erl-csurf --save
```

To use in your app:

```javascript
app.use(cookieParser());
csurf({ cookie: true });

// ...declare all your other routes and middleware
```


Fork and reference of https://github.com/ashrith-kulai/express-csurf

The official repo doesn't support manual token verification.
Hence this fork. 

## License

[MIT](LICENSE)
