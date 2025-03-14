# Happy Birthday Card

A Customizable Web-based birthday card to wish your friends and family in a unique way.

Check out the Previews -

- [With Scroll Message](https://hbd-card.netlify.app/)

If you liked it, please consider giving it star a 🤩⭐. You can also support me by sponsoring.

---

## How to setup

Here are the methods to set it up for yourself.

### Remote Deployment

- Netlify Deploy

   [![Deploy with NEtlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/hackerkdx/Happy-Birthday)

Remote deployment will require you to specify some mandatory environmental variables,

- NAME: Name of the receiver.
- PIC: Url of the pic to be loaded in the card. If don't have the image hosted somewhere, you may publish a [telegra.ph article](https://telegra.ph) with your image and copy the image address from there.

To know more about the environment variables, check [References](#references).

### For Local Building

1. Clone the repository

```sh
git clone https://github.com/AnshumanMahato/Happy-Birthday-Card

```

2. Install dependencies

```sh
npm install

```

3. Add a pic of the receiver, in the `./local` directory. Ensure that the image is of a 1:1 ratio or it might get cropped and squished.

4. Create a `.env` file in the root directory, and add the following lines.

```env
 NAME='Name of the Receiever'
 PIC='name-of-image.extension'

```

5. Execute the following commands in order.

```sh
 npm run init-index-local
 npm run build:parcel

```

6. Upon Successful execution, your built files will be ready in the `./dist` directory. Serve this directory using `live-server` or similar tools to see your card.

For further customization, check out [here](./docs/customizations.md).

---

## References

- [Environment Variables](./docs/variables.md)
- [Attributions](./docs/attributions.md)

---

## Support

If you have any queries or need some help in deployment, you may contact me here

- [Telegram](https://t.me/AnshumanMahato)
- [Email](mailto:rcoder.bytes@gmail.com)

<div align="center">
Made with 💖 by Anshuman Mahato
</div>

