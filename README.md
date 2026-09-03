<div align="center">

# MD EBRAHIM NAZMUL

### Flutter Developer · Building production mobile apps end-to-end, from architecture to App Store release

<img src="https://komarev.com/ghpvc/?username=parentroots&label=Profile%20Views&color=0e75b6&style=flat-square" alt="views" />
<img src="https://img.shields.io/github/followers/parentroots?label=Followers&style=flat-square&color=blue" alt="followers" />
<img src="https://img.shields.io/badge/Open%20to-Freelance%20%2F%20Full--time-brightgreen?style=flat-square" alt="availability" />
<img src="https://img.shields.io/badge/Based%20in-Dhaka%2C%20Bangladesh-orange?style=flat-square" alt="location" />

<a href="#"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/parentroots"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /></a>

</div>

<br/>

## About Me

I'm a Flutter Developer at **Betopia Limited**, Dhaka — I build cross-platform mobile apps from scratch and take them all the way through to **Play Store** and **App Store** release, including compliance and rejection handling. I started in native Android with Java before moving fully into Flutter.

```
🔭 Currently building     mobile applications across multiple client & personal projects
🌱 Currently learning     Riverpod (migrating architectural thinking from GetX)
🛠  Daily stack            Flutter · Dart · GetX · Firebase · REST APIs · Socket.IO
📦 Shipped through        Google Play Console & Apple App Store, incl. compliance/rejections
⚡ Fun fact                I'll spend an hour fixing one pixel of UI misalignment
```

<br/>

## Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**Language & Framework**

<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
<img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" />

**State Management**

<img src="https://img.shields.io/badge/GetX-5C2D91?style=for-the-badge" />
<img src="https://img.shields.io/badge/Riverpod-40C4FF?style=for-the-badge" />

</td>
<td valign="top" width="50%">

**Backend & Realtime**

<img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
<img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
<img src="https://img.shields.io/badge/REST%20API-005571?style=for-the-badge" />

**Payments & Tools**

<img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white" />
<img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />

</td>
</tr>
</table>

**Architecture I follow on every project:**
`Model → ApiClient (Dio) → Repository → GetX Controller → UI`
Feature-based folder structure (`screens/feature_name/`) with a reusable component library — `CommonText`, `CommonButton`, `CommonTextField`, `CommonAppBar`, `CommonScaffold`, `CommonTopBar`.

<br/>

## Featured Projects

<table>
<tr>
<td width="60">🏥</td>
<td>

### Permawell Health Care — Doctor Booking App
**Status:** `Private / Client Project`

Connects patients with doctors for appointment booking, removing the friction of calls or walk-ins.

| What I built | |
|---|---|
| Auth | Dual sign-up/login flows for **Doctor** and **Patient** roles |
| Booking | Appointment **create & cancel** flow |
| Payments | In-app **payment** integration for consultations |
| Communication | Real-time **messaging** between doctor and patient |

<p align="left">
  <img src="images/permawell_home.png" height="300" alt="Patient Home & Doctor Search" />
  <img src="images/permawell_doctor_detail.png" height="300" alt="Doctor Profile & Reviews" />
</p>

`Flutter` `GetX` `Firebase` `REST API` `Payment Gateway`

</td>
</tr>

<tr>
<td width="60">📦</td>
<td>

### MileSquad — Parcel Delivery App
**Status:** `Private / Client Project`

A two-sided parcel delivery platform, shipped as **separate Customer and Rider apps**, connecting people who need to send parcels with riders who deliver them.

| What I built | |
|---|---|
| Customer app | Parcel **creation** flow — pickup/drop details, request submission |
| Rider app | **Accept/assign** flow for incoming delivery requests |
| Live tracking | **Real-time map tracking** over sockets for both customer and rider |
| Communication | In-app **messaging** between customer and rider |

<br/>

<p align="left">
  <img src="images/milesquad_customer.png" height="300" alt="Customer App - Location & Order Creation" />
  <img src="images/milesquad_tracking.png" height="300" alt="Live Map Tracking Screen" />
  <img src="images/milesquad_rider.png" height="300" alt="Rider App - Requests & Earnings" />
</p>

<br/>

`Flutter` `GetX` `Socket.IO` `Google Maps` `Firebase`

</td>
</tr>

<tr>
<td width="60">⚖️</td>
<td>

### Panama Legal — Multi-Role Legal Services Platform
**Status:** `Private / Client Project`

Bridges citizens and lawyers on one platform for legal consultation, document access, and case communication.

| What I built | |
|---|---|
| Chat | Migrated citizen–lawyer chat from REST to **Socket.IO**, added multipart file attachments |
| Chatbot | Recursive sub-question navigation for legal query triage |
| Documents | Searchable **PDF viewer** (Syncfusion) + paginated **law library** |
| Polish | Profile, logout, and terms screens refined; primary resume project with iteratively tuned write-ups |

`Flutter` `GetX` `Socket.IO` `Syncfusion PDF` `REST API`

</td>
</tr>

<tr>
<td width="60">📍</td>
<td>

### Giolee78 (Just Clicker) — Social / Location-Based App
**Status:** `Private / Client Project` · Live on Play Store & App Store (client-owned listing)

A location-aware social app connecting nearby users, with in-app purchases and ad-supported screens.

| What I built | |
|---|---|
| Notifications | Fixed **FCM navigation** bugs across all app lifecycle states |
| Payments | Built **Stripe WebView** flow, later migrated to **native IAP** for App Store compliance |
| Auth | Resolved **Google Sign-In SHA-1 / DEVELOPER_ERROR** issues |
| Store compliance | Play Console (AD_ID, delete-account URL, CSAE policy, content rating) + fixed multiple App Store rejections (location permissions, IAP, UGC moderation, iPad bugs) |
| UI | Redesigned `ViewAdsScreen` and `DashboardScreen` |

`Flutter` `GetX` `Firebase Cloud Messaging` `Stripe` `In-App Purchases`

</td>
</tr>

<tr>
<td width="60">🍔</td>
<td>

### Brain Denner (Fastfood Buddy) — Food & Health Tracking App
**Status:** `Private / Client Project`

Helps users track meals, restaurant choices, and nutrition history in one place.

| What I built | |
|---|---|
| Discovery | Restaurant details screen + paginated **history list** |
| Bug fix | Fixed critical `BeforeYouEatScreen` navigation/data bug from GetX controller caching |
| Insights | Integrated **Buddy Insights API** for personalized recommendations |

`Flutter` `GetX` `REST API`

</td>
</tr>
</table>

<br/>

## Let's Connect

Open to **Junior/Mid Flutter Developer** roles and freelance mobile projects.

<div align="center">
<a href="#"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<h3>🔥 "Eat → Code → Sleep → Repeat" 🔥</h3>
</div>
