Auto-Renew-hostship

环境变量:
  HS_API_KEY       面板 Client API Key (ptlc_ 开头)          [必填]
  HS_SERVER_ID     服务器 identifier, 即 /server/xxx 里那段   [默认 c12fd5d9]
  HS_PANEL_URL     面板地址                                   [默认 https://panel.host-ship.com]
  RENEW_THRESHOLD  剩余天数 <= 该值时才续期                    [默认 4]
  TG_BOT_TOKEN     Telegram Bot Token                        [可选, 不填则不通知]
  TG_CHAT_ID       Telegram Chat ID                          [可选]
