NOTE: 运行examples前请创建 `.env` 文件.

$ cat .env

GMEX_HTTP_URL_MARKET=https://api-market.gmex.io/v1/rest
GMEX_HTTP_URL_TRADE=https://api-trade.gmex.io/v1/rest

GMEX_WS_URL_MARKET=wss://api-market.gmex.io/v1/market
GMEX_WS_URL_TRADE=wss://api-trade.gmex.io/v1/trade

GMEX_USER_NAME=<your@email.com>
GMEX_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxx
GMEX_API_SECRET=yyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy

跑例子试试：
cd examples/http_client; cargo run
cd examples/websocket_client; cargo run

