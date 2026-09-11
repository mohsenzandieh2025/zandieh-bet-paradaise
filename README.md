# zandieh-bet-paradaise
# 🏆 Zandie Bet Paradise

Faucet ارز دیجیتال با اتصال TRON (TRC20)

## Deploy روی Render

1. این مخزن را به GitHub push کن
2. به https://dashboard.render.com/blueprints برو
3. **New Blueprint Instance** → مخزن را انتخاب کن
4. متغیرهای محیطی را پر کن (TRON_PRIVATE_KEY, etc.)
5. **Apply** → هر دو سرویس ساخته می‌شوند

## متغیرهای محیطی

| متغیر | توضیح |
|-------|-------|
| `SITE_URL` | آدرس فرانت‌اند (بعد از ساخت: `https://zandie-bet-frontend.onrender.com`) |
| `TRON_PRIVATE_KEY` | کلید خصوصی کیف پول فاست |
| `FAUCET_WALLET_ADDRESS` | آدرس TRC20 کیف پول فاست |
| `ADMIN_PASSWORD` | رمز قوی برای ادمین |
