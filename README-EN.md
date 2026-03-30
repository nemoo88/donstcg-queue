# 🎴 TCG Queue System - Demo

A demo version of the TCG Live Rip n Ship Queue System for GitHub Pages.

## 🚀 Live Demo

Visit: [`https://nemooo88.github.io/tcg-queue-demo/`](https://nemooo88.github.io/tcg-queue-demo/)

## ✨ Demo Features

- ✅ **Admin panel** with full functionality (password protected)
- ✅ **Multiple products per order** - Add "2 pack Pika, 3 pack Booster" on same line
- ✅ **⏭️ Skip** - Postpone orders to end of queue (both in queue and open)
- ✅ **⏭️ Postpone open** - Postpone current order and open next
- ✅ **OPEN button** for all orders (including events)
- ✅ **✕ Remove button** for all orders
- ✅ **🕐 Time since** order came in
- ✅ **Events** with pink background (Giveaway, Duckrace, etc.)
- ✅ **OBS Overlay** - Shows queue with both Rip n Ship and Events
- ✅ **Dynamic time calculation** - System learns your pace and updates estimation
- ✅ **🔄 Reset statistics** - Keeps queue, resets numbers
- ✅ **Automatic next** - Next order opens at "Done - Next"

## ⚠️ Limitations (Demo)

- Data is only saved in browser (localStorage)
- Everything disappears if you clear cache or switch browser
- No Shopify integration (manual entry)
- No permanent storage

## 🔐 Security

Admin panel is password protected. To test:
- **Demo password:** `demo123`

In the full version, you can change to your own password in `admin/index.html`.

## 🎮 How to Use the Demo

1. **Go to admin panel** (`/admin/`)
2. **Log in with password:** `demo123`
3. **Click "🎲 Load demo data"** to get some test orders
4. **Test the buttons:**
   - **⏭️** - Postpone order to end of queue
   - **OPEN** - Open order on stream
   - **✕** - Remove order
   - **✓ Done - Next** - Mark done and open next automatically
5. **Open overlay** in new tab to see how it looks in OBS

## 🛒 Full Version

Contact for full version with:
- Shopify integration (automatic orders)
- Netlify Blob Storage (permanent storage)
- HMAC verification (security)
- Custom branding

---

**© 2026 TCG Queue System – Demo Version**
