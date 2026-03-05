# hedgehog-media-web
import QRCodeStyling from "qr-code-styling";

const qrCode = new QRCodeStyling({
  width: 300,
  height: 300,
  data: "https://github.com/yourusername/yourrepo",
  image: "logo.png",
  dotsOptions: {
    color: "#000000",
    type: "rounded"
  },
  backgroundOptions: {
    color: "#ffffff"
  },
  imageOptions: {
    crossOrigin: "anonymous",
    margin: 10
  }
});
