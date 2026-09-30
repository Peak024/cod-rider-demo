# COD Rider & Customer Demo

Clickable concept demo of the cash-on-delivery (COD) doorstep flow.

- **Rider app** — the four outcomes a rider can record: normal delivery, refused but saved with an on-the-spot discount (rider bonus), refused and returned to hub, and silent rejection closed with a GPS-tagged photo.
- **Customer streak** — the buyer-side reward ladder for consecutive successful COD pickups, and the reset rule on refusal.
- **Green / Yellow / Red customer** — the same ฿550 order at a Shopee-style checkout for three risk tiers, each with a Shopee Voucher picker:
  - **Green:** normal checkout. Cash on delivery available, and vouchers work with every payment method.
  - **Yellow:** COD needs a 20% deposit paid in the app first. Vouchers can't be combined with COD; switching to COD removes an applied voucher. Prepaid methods take vouchers as normal.
  - **Red:** COD suspended, prepay only. Vouchers work with the prepaid methods.

Thai / English switch in the top bar (remembered per browser). On phones the app fills the screen; on tablets and desktops it is shown inside a phone frame.

Single static file: `index.html` (Tailwind, Lucide and the Prompt font load from CDNs). Deployed on Vercel.
