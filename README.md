# LEETCODE-Arrays-1437
```
nums = [1,0,0,0,1,0,0,1]
k = 2
```

Code:

```java
int n = nums.length;      // n = 8
int last = -(k+1);        // last = -(2+1) = -3
```

---

# 🔍 **Dry Run (Index by Index)**

### **i = 0**

```
nums[0] = 1
Check: (i - last - 1) < k ?
       (0 - (-3) - 1) = (0 + 3 - 1) = 2
       2 < 2 ? NO
```

So ok.

Update:

```
last = 0
```

---

### **i = 1**

```
nums[1] = 0 → skip
```

---

### **i = 2**

```
nums[2] = 0 → skip
```

---

### **i = 3**

```
nums[3] = 0 → skip
```

---

### **i = 4**

```
nums[4] = 1
Check: (i - last - 1) < k ?
       (4 - 0 - 1) = 3
       3 < 2 ? NO
```

So ok.

Update:

```
last = 4
```

---

### **i = 5**

```
nums[5] = 0 → skip
```

---

### **i = 6**

```
nums[6] = 0 → skip
```

---

### **i = 7**

```
nums[7] = 1
Check: (i - last - 1) < k ?
       (7 - 4 - 1) = 2
       2 < 2 ? NO
```

So ok.

Update:

```
last = 7
```

---

# ✔ Loop completes with no false condition

So the function returns:

```
true
```

---

# ⭐ Final Result: **true**
