# COD Rider & Customer Demo

Clickable concept demo of the cash-on-delivery (COD) doorstep flow.

- **Rider app** — the four outcomes a rider can record: normal delivery, refused but saved with an on-the-spot discount (rider bonus), refused and returned to hub, and silent rejection closed with a GPS-tagged photo.
- **Customer streak** — the buyer-side reward ladder for consecutive successful COD pickups, and the reset rule on refusal.
- **Green / Yellow / Red customer** — the same ฿550 order at a Shopee-style checkout for three risk tiers:
  - **Green:** normal checkout, cash on delivery available.
  - **Yellow:** COD needs a 20% deposit paid in the app first (the rest is paid to the rider), with the reasons shown and how to lift it.
  - **Red:** COD suspended for 30 days, prepay only, with the reasons shown and when it comes back.

Thai / English switch in the top bar (remembered per browser). On phones the app fills the screen; on tablets and desktops it is shown inside a phone frame.

Single static file: `index.html` (Tailwind, Lucide and the Prompt font load from CDNs). Deployed on Vercel.
