# AHK-Pushover-Notify
AHK Script to send a push notification to the Pushover.net API

Usage:

`#Include URLEncode.ahk

payloadString := BuildPayload("api-key", "user-key", "title", "message")
SendNotification(payloadString)

That's it
