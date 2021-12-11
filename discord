#!/bin/bash
message="$@"
msg_content=\"$message\"

url="https://discord.com/api/webhooks/837696031507480627/xXJLsJ1EsSiBAqK3kakzGxSAz5S16YDqPbuR_lvT0LDP-MlgVu-ULBWYiHPjSX7Npjia"
curl -H "Content-Type: application/json" -X POST -d "{\"content\": $msg_content}" $url
