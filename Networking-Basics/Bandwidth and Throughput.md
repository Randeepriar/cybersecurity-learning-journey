# Bandwidth and Throughput

## 1.3.1 Bandwidth

### What is Bandwidth?

**Bandwidth** is the capacity of a network medium to carry data.

Digital bandwidth measures the amount of data that can theoretically flow from one place to another in a given amount of time.

Bandwidth is typically measured in **bits per second (bps)**.

### Common Bandwidth Units

| Unit | Abbreviation | Equivalent |
|---|---|---|
| Bits per second | **bps** | 1 bps |
| Kilobits per second | **Kbps** | 1 Kbps = 1,000 bps = 10³ bps |
| Megabits per second | **Mbps** | 1 Mbps = 1,000,000 bps = 10⁶ bps |
| Gigabits per second | **Gbps** | 1 Gbps = 1,000,000,000 bps = 10⁹ bps |
| Terabits per second | **Tbps** | 1 Tbps = 1,000,000,000,000 bps = 10¹² bps |

### Factors Affecting Available Bandwidth

The available bandwidth depends on:

- Properties of the physical media
- Current technologies
- Laws of physics

### Important Point

Bandwidth represents the **theoretical capacity** of a network connection. It does not necessarily represent the amount of data that is actually transferred.

**Remember:**

> **Bandwidth = How much data the network can theoretically carry per second**

---

## 1.3.2 Throughput

**Throughput** is the actual rate at which bits are transferred across the network media over a given period of time.

Unlike bandwidth, throughput does not usually reach the specified bandwidth because several factors can affect the actual data transfer rate.

### Factors Affecting Throughput

#### 1. Amount of Data Being Sent and Received

The amount of traffic being transmitted over a connection can affect the actual throughput.

#### 2. Type of Data Being Transmitted

Different types of data can affect how efficiently the network transfers information.

#### 3. Latency

**Latency** is the amount of time, including delays, required for data to travel from one point to another.

For example:

```text
Source → Network Devices → Destination
```

The number of network devices and links encountered along the path can contribute to latency.

---

## Throughput and Network Traffic

Throughput measures the transfer of bits, but it does not determine whether those bits are useful to a particular user application.

Some network traffic consists of **control messages** that help:

- Regulate network traffic
- Correct errors
- Manage communication

These bits contribute to the total data being transmitted even though they may not represent user data.

---

## The Slowest Link

In a network with multiple segments, the throughput cannot be faster than the **slowest link** in the path between the sending and receiving devices.

For example:

```text
Computer
   ↓
100 Mbps
   ↓
Router
   ↓
10 Mbps
   ↓
Router
   ↓
100 Mbps
   ↓
Server
```

Even though most links support **100 Mbps**, the **10 Mbps link** limits the throughput of the entire path.

The slowest link is called a **bottleneck**.

### Remember

> **Slowest Link = Bottleneck = Limits Throughput**

---

## Bandwidth vs Throughput

| Bandwidth | Throughput |
|---|---|
| Theoretical capacity | Actual data transfer rate |
| Describes how much data can theoretically be carried | Describes how much data is actually transferred |
| Measured in bits per second | Measured in bits per second |
| Usually represents the maximum possible rate | Usually lower than the available bandwidth |
| Does not account for network conditions | Affected by network conditions |

### Simple Example

If a network connection has:

**Bandwidth = 100 Mbps**

but only **70 Mbps** of data is actually transferred, then:

**Throughput = 70 Mbps**

Therefore:

> **Throughput is normally less than or equal to bandwidth.**

---

## Internet Speed Tests

Online speed tests can be used to determine the **throughput** of an internet connection.

For example, if an internet connection has a specified capacity of 100 Mbps but a speed test measures 80 Mbps, the measured 80 Mbps represents the actual throughput at that time.

---

# Quick Revision

### Bandwidth

- Capacity of a network medium
- Represents the **theoretical maximum** data transfer rate
- Measured in **bits per second**
- Common units: **bps, Kbps, Mbps, Gbps, Tbps**

### Throughput

- Actual rate of data transfer
- Usually does not match the specified bandwidth
- Affected by:
  - Amount of data being sent/received
  - Type of data
  - Latency
  - Network path conditions

### Latency

> The time, including delays, required for data to travel from one point to another.

### Bottleneck

> The slowest link in a network path that limits overall throughput.

### Key Relationship

```text
Bandwidth = Theoretical Capacity
Throughput = Actual Transfer Rate
```

**Throughput ≤ Bandwidth**

### Easy Memory Trick

**Bandwidth = CAN carry**

**Throughput = ACTUALLY carries**

**Latency = DELAY**

**Bottleneck = SLOWEST LINK**
