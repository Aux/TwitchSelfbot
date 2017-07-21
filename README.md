Uses NTwitch version `0.1.2-build-00007`

# Twitchbot
A generic twitch chat bot, provided as an example for the [NTwitch](https://github.com/Aux/NTwitch) library.

#### Example config.yml
```yaml
# A Twitch oauth token the bot will use to log in to chat
token: yourtokenhere

# Channels the bot will join after connecting to chat
channels:
  - auxesistv
  - shiralya

# All events the bot should reply to. Replies are
# randomly selected from list provided for each event
#
# Available events: new_sub, re_sub, hosting_started, 
# hosting_ended, hosted_started, hosted_ended, user_banned
events:
  new_sub:
    - Thanks for subscribing %user% Kappa
    - Thank you for the sub %user% LUL
  re_sub:
    - Wow! %user% resubscribed for %months% month(s)
```
