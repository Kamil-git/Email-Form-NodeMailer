NodeMailer - contact form for sending emails from your website

const transporter = nodemailer.createTransport({
  host: 'smtp.gmail.com',
  port: 465,
  auth: {
    user: process.env.EMAIL, // your email
    pass: process.env.PASS, // your password
  },
});
