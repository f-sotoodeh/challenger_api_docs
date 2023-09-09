# Challenger API docs

## 1. User
- [sign](./1_user/1_sign.md) (sign-in/sign-out/sign-up)
- [profile](./1_user/2_profile.md) (get/update user profile)
- [password](./1_user/3_password.md) (reset password)
- [session](./1_user/4_session.md) (get all sessions and close one)
- [user](./1_user/5_user.md) (*get all users)

## 2. Challenge
- [challenge](./2_challenge/1_challenge.md) (CRUD)
- [story](./2_challenge/2_story.md) (CRU)
- [pro_profile](./2_challenge/3_pro_profile.md) (RU)

## 3. Hit
- [viewed](./3_hit/1_viewed.md) (CR)
- [stared](./3_hit/2_stared.md) (CRD)
- [followed](./3_hit/3_followed.md) (CRD)

## 4. Other
- [prize](./4_other/1_prize.md) (CRUD)
- [bet](./4_other/2_bet.md) (CRUD)
- [news](./4_other/3_news.md) (R/*CUD)

## 5. Message
- [wall](./5_message/1_wall.md) ()
- [debate](./5_message/2_debate.md) (CRU)
- [room](./5_message/3_room.md) (CRU)
- [chat](./5_message/4_chat.md) (CRU)
- [passepartoute chat](./5_message/5_p_chat.md) ()
- [passepartoute media](./5_message/6_p_media.md) ()
- [passepartoute share](./5_message/7_p_share.md) ()



---
## Pagination
Some endpoints support pagination
### parameters

- page_number
- page_size
- order_by

All parameters are optional

```
...?page_number=2
...?page_size=10
...?page_number=2&page_size=10
...?page_number=2&page_size=10&order_by=name
...?page_number=2&page_size=10&order_by=-name
```