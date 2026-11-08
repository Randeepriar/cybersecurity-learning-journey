# Data Transmission

## 1.2.1 Types of Personal Data

Personal data can be classified into three main types:

### 1. Volunteer Data

Data that a person **deliberately provides**.

**Examples:**
- Name
- Email address
- Phone number
- Address
- Information entered into an online form
- Photos or posts uploaded by the user

**Remember:**  
> Volunteer Data = **You provide it**

---

### 2. Observed Data

Data that is **collected by observing a person's activities or behavior**.

**Examples:**
- Websites visited
- Location data
- Browsing activity
- Device information
- App usage

**Remember:**  
> Observed Data = **System observes it**

---

### 3. Inferred Data

Data that is **derived, estimated, or predicted from other available data**.

**Example:**

If a user frequently searches for laptops, visits technology websites, and watches laptop reviews, a system may **infer** that the user is interested in buying a laptop.

**Remember:**  
> Inferred Data = **System figures it out**

### Quick Comparison

| Type | Meaning | Example |
|---|---|---|
| **Volunteer** | User deliberately provides the data | Name, email |
| **Observed** | User's activity is observed/collected | Location, browsing activity |
| **Inferred** | Information is derived or predicted | Interests, preferences |

---

## 1.2.2 The Bit

A **bit** is the smallest unit of data used by computers.

The word **bit** is short for **binary digit**.

A bit can have only two possible values:

**0 or 1**

These two values can represent two different physical states, such as:

- On / Off
- Two electrical levels
- Two magnetic states
- Two levels of light intensity

### Input and Output

Input devices such as keyboards, mice, and voice-activated devices convert human interaction into **binary data** that the computer can process and store.

Output devices such as monitors, speakers, and printers convert **binary data** back into a form that humans can understand.

### ASCII

**ASCII (American Standard Code for Information Interchange)** is a character encoding system used to represent characters digitally.

Examples:

```text
A → 01000001
9 → 00111001
# → 00100011
```

Each group of **8 bits** is called a **byte**.

### Bit vs Byte

- **1 bit** = one binary digit (`0` or `1`)
- **1 byte** = **8 bits**

---

## 1.2.3 Common Methods of Data Transmission

After data is converted into a series of bits, it must be converted into **signals** so that it can travel across network media.

### Network Media

**Media** refers to the physical medium through which signals are transmitted.

Examples:

- Copper wire
- Fiber-optic cable
- Air for wireless communication

A **signal** is an electrical, optical, or electromagnetic pattern used to represent digital data and carry it from one device to another.

---

## Three Common Methods of Signal Transmission

### 1. Electrical Signals

Data is represented as **electrical pulses** and transmitted through copper wires.

**Example:**

```text
Data → Electrical pulses → Copper cable
```

**Remember:**  
> Copper → Electricity

---

### 2. Optical Signals

Data is converted into **pulses of light** and transmitted through fiber-optic cables.

**Example:**

```text
Data → Light pulses → Fiber-optic cable
```

Fiber-optic cables are commonly used to reliably carry signals over **longer distances**.

**Remember:**  
> Fiber → Light

---

### 3. Wireless Signals

Data is transmitted through the air using electromagnetic waves.

Examples include:

- Radio waves
- Microwaves
- Infrared

**Example:**

```text
Data → Radio waves → Air → Receiving device
```

**Remember:**  
> Wireless → Electromagnetic waves

---

## Signal Conversion

Signals may be **converted multiple times** as they travel from the source to the destination because the type of network media may change.

For example:

```text
Computer
   ↓
Copper cable
   ↓
Router
   ↓
Fiber-optic cable
   ↓
Router
   ↓
Wireless
   ↓
Phone
```

The signal can therefore change form as it passes through different types of network media.

---

# Quick Revision

### Personal Data

| Type | Meaning |
|---|---|
| **Volunteer Data** | Data deliberately provided by the user |
| **Observed Data** | Data collected by observing activity |
| **Inferred Data** | Data derived or predicted from other data |

### Basic Data Units

- **Bit** = 0 or 1
- **Byte** = 8 bits
- **ASCII** = character encoding system

### Signal Transmission

| Method | Signal | Medium |
|---|---|---|
| **Electrical** | Electrical pulses | Copper |
| **Optical** | Light pulses | Fiber-optic cable |
| **Wireless** | Electromagnetic/radio waves | Air |

### Key Flow

```text
Data
 ↓
Bits
 ↓
Signals
 ↓
Network Media
 ↓
Destination
```

### Easy Memory Trick

**Copper = Electricity ⚡**  
**Fiber = Light 💡**  
**Wireless = Radio Waves 📡**

**Volunteer = Provide**  
**Observed = Watch**  
**Inferred = Figure Out**
