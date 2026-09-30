# COD Rider & Customer Demo

Clickable concept demo of the cash-on-delivery (COD) doorstep flow.

- **Rider app** — the four outcomes a rider can record: normal delivery, refused but saved with an on-the-spot discount (rider bonus), refused and returned to hub, and silent rejection closed with a GPS-tagged photo.
- **Customer streak** — the buyer-side reward ladder for consecutive successful COD pickups, and the reset rule on refusal.
- **Green / Yellow / Red customer** — the same jacket at a Shopee-style checkout for three risk tiers, with a quantity selector and a Shopee Voucher picker:
  - **Green:** nothing restricted. COD as normal, vouchers in full, and the order joins the Priority delivery queue.
  - **Yellow:** COD with conditions: one-tap order confirmation by SMS/LINE before packing, a ฿2,000 COD limit, no vouchers with COD, and a 20% deposit only on orders over ฿1,000. Paying in advance lifts every condition, vouchers included.
  - **Red:** no COD, prepay only (ShopeePay, bank transfer, card or QR). Buying is otherwise normal and the only message is "COD isn't available for this order".

Thai / English switch in the top bar (remembered per browser). On phones the app fills the screen; on tablets and desktops it is shown inside a phone frame.

Single static file: `index.html` (Tailwind, Lucide and the Prompt font load from CDNs). Deployed on Vercel.
