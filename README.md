# COD Rider & Customer Demo

Clickable concept demo of the cash-on-delivery (COD) doorstep flow.

- **Rider app** — the four outcomes a rider can record: normal delivery, refused but saved with an on-the-spot discount (rider bonus), refused and returned to hub, and silent rejection closed with a GPS-tagged photo.
- **Customer streak** — the buyer-side reward ladder for consecutive successful COD pickups, and the reset rule on refusal.
- **Green / Yellow / Red customer** — the same jacket at a Shopee-style checkout for three risk tiers, with a quantity selector and a Shopee Voucher picker:
  - **Green:** normal checkout. Cash on delivery available, and vouchers work with every payment method.
  - **Yellow:** COD with conditions instead of a deposit: no vouchers with COD, a ฿1,000 cap on the COD order, at most 2 items, and an order confirmation pop-up where the customer ticks that they will be there to pay the rider. A cart over the limits locks COD until another method is chosen or the quantity is reduced. Prepaid methods work normally, vouchers included.
  - **Red:** COD suspended, prepay only. Vouchers work with the prepaid methods.

Thai / English switch in the top bar (remembered per browser). On phones the app fills the screen; on tablets and desktops it is shown inside a phone frame.

Single static file: `index.html` (Tailwind, Lucide and the Prompt font load from CDNs). Deployed on Vercel.
