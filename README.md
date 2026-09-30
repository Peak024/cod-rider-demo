# COD Rider & Customer Demo

Clickable concept demo of the cash-on-delivery (COD) doorstep flow.

- **Rider app** — the four outcomes a rider can record: normal delivery, refused but saved with an on-the-spot discount (rider bonus), refused and returned to hub, and silent rejection closed with a GPS-tagged photo.
- **Customer streak** — the buyer-side reward ladder for consecutive successful COD pickups, and the reset rule on refusal.
- **Green / Yellow / Red customer** — the same jacket at a Shopee-style checkout for three risk tiers, with a quantity selector and a Shopee Voucher picker:
  - **Green:** nothing restricted. COD as normal, vouchers in full, and the order joins the Priority delivery queue.
  - **Yellow:** cash on delivery (เก็บเงินปลายทาง) with one condition: a one-tap order confirmation by SMS/LINE before packing. Shopee Vouchers are not available with any payment method, and paying in advance skips the confirmation.
  - **Red:** cash on delivery suspended for 30 days. The option is locked and shows the date it comes back; prepaid methods (ShopeePay, bank transfer, card, QR) and vouchers work as normal.

Thai / English switch in the top bar (remembered per browser). On phones the app fills the screen; on tablets and desktops it is shown inside a phone frame.

Single static file: `index.html` (Tailwind, Lucide and the Prompt font load from CDNs). Deployed on Vercel.
