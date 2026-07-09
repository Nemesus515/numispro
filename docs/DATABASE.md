# Database

Status: Draft

## Overview

NumisPro uses PostgreSQL as the primary database.

The database is designed around several core entities:

- User
- Coin
- Collection
- CollectionItem
- Series
- Variety
- MarketPrice
- Achievement
- Comment

---

# User

Stores user account information.

Main fields:

- id
- username
- email
- password_hash
- avatar
- country
- created_at

---

# Coin

Stores catalog information.

Main fields:

- id
- country
- denomination
- year
- mint
- material
- weight
- diameter
- thickness
- mintage
- description

---

# Collection

A user can create multiple collections.

Examples:

- USSR
- Russia
- Foreign coins
- For sale
- Wishlist

---

# CollectionItem

Stores a specific coin owned by a user.

Main fields:

- id
- user_id
- collection_id
- coin_id
- grade
- purchase_price
- purchase_date
- current_value
- storage_location
- notes

---

# Series

Stores coin series.

Examples:

- Cities of Military Glory
- Red Book
- Olympic Games

---

# Variety

Stores varieties of the same coin.

Examples:

- Mint marks
- Die varieties
- Errors

---

# MarketPrice

Stores historical market prices.

Main fields:

- coin_id
- date
- minimum_price
- average_price
- maximum_price

---

# Achievement

Stores all achievements available in NumisPro.

---

# UserAchievement

Stores achievements earned by users.

---

# Comment

Stores comments for coins.

---

# Photo

Stores user uploaded images.

---

# Activity

Stores user activity history.

Examples:

- Added coin
- Updated collection
- Uploaded photo
- Earned achievement

---

## Future tables

- Marketplace
- Auctions
- Messages
- Clubs
- Events
- AI Recognition
