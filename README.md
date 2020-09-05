# Nebulous API Documentation(Unoffical)
### Note
This may not be the complete API. There may have been some endpoints I looked over on older versions of the game.

Check out the `work-in-progress` branch to see the latest updates on the documentation! :D

| Domain | www.simplicialsoftware.com |
|:---|:---|
| Path | /api/account/ |
| Method | POST |
| Content-Type | application/x-www-form-urlencoded |

### GoogleLogin
#### Parameters
| Name | Description |
|:---|:---|
| Game | Name of the game (Nebulous, Orborous, Rebellious) |
| Version | Game version code |
| authToken | Google authentication token |
| FirebaseToken | Firebase token |

#### Response(JSON)
| Name | Description | Type |
|:---|:---|:---|
| UserName | Account username | String |
| AccountColors | Account bio colors | Array |
| Ticket | Account login ticket | String |
| Coins | Account plasma count | Long |
| BanUntilUtc | Ban duration | String |
| banReason | Reason for ban | String |
| clanID | Account clan ID | Integer |
| ClanName | Account clan name | String |
| ClanColors | Account clan name colors | Array |
| ClanRole | Role in clan | String |
| ClanCoins | Clan plasma count | Long |
| EffectiveClanRole | Unknown | String |
| CanSelfPromote | Can self promote in the clan | Boolean |
| Error | Error message | String |

**I am not affiliated with Simplical Software or any of it's affiliates.**
