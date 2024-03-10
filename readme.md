# quickconfirm-email Node.js SDK

Node.js library for the Quick Confirm E-mail API.

## Install

```bash
npm install quickconfirm-email
# or
```

## Usage

Send your first email:

```js
await resend.emails.send({
  from: 'you@example.com',
  to: 'user@gmail.com',
  subject: 'hello world',
  text: 'it works!',
});
```

## License

MIT License
