
# Slide 1

- l1
  - l1 1
- l2
- l3
  
<!-- images may be inserted and size like this -->
![myimage](/images/myimage.png){style="width: 10%;"}
<!-- or with Tailwind CSS styles -->
<!-- centered (.mx-auto)-->
![myimage](/images/myimage.png){.block .mx-auto .w-1/8}

---

# Code 1

````md magic-move {lines: true}
```java
import java.util.List;
import java.util.ArrayList;

java.util.List<String> list = new java.util.ArrayList<String>();
```

```java
import java.util.List;
import java.util.ArrayList;

java.util.List<String> list = new java.util.ArrayList<String>();
list.add("an object");
list.add("another objet");
```

```java
import java.util.List;
import java.util.ArrayList;

java.util.List<String> list = new java.util.ArrayList<String>();
list.add("an object");
list.add("another object");

System.out.println("second element of the list: " + list.get(1));
list.clear();

```
````

---

# Code 2

This code section is editable (but not runnable...yet)

```java{monaco}
import java.util.List;
import java.util.ArrayList;

java.util.List<String> list = new java.util.ArrayList<String>();
```

---

# Clicks Animations

<v-click>
This is <span v-mark.red="1">very important</span>
</v-click>
<v-click>
This is <span v-mark.circle.orange="2">too</span>
</v-click>

---

# Annotated JSON

<style>
/* Add your custom styles here */
.text-box {  
  position: relative;
  display: inline-block;
  font-size: 8pt;
  padding: 3px 5px;
  background-color: #FFFF66;
  border: 1px solid #aaa;
  border-radius: 3px;
}

.tb1 {
  position: relative;
  top: 0mm; left: 100mm;
}
</style>

<!-- Add your custom HTML here -->
<div class="text-box tb1">
  This is a floating text box.  
</div>


```json
{
  "name": "Slidev",
  "description": "Presentation Slides for Developers (Presentation Slides for Developers)"
}
```

---
layout: image
image: https://logos-marques.com/wp-content/uploads/2021/03/Android-Logo.png

---
# background image with component overlay on click

<v-click>
<div
  v-motion
  :initial="{ y: -80 }"
  :enter="{ y: 0 }"
  :click-1="{ y: 40 }"
  :leave="{ y: 1000 }"
>
  <Arrow x1="30mm" y1="30mm" x2="70mm" y2="30mm" width="1" color="#777"/>
</div>
</v-click>

---

# 3 column layout

3 column layout

<div class="grid grid-cols-[33%_33%_33%] gap-none">
<div>
```java
import java.util.List;
import java.util.ArrayList;

java.util.List<String> list = new java.util.ArrayList<String>();
list.add("an object");
list.add("another object");

System.out.println("second element of the list: " + list.get(1));
list.clear();
```
</div>
<div>
```java
import java.util.List;
import java.util.ArrayList;

java.util.List<String> list = new java.util.ArrayList<String>();
list.add("an object");
list.add("another object");

System.out.println("second element of the list: " + list.get(1));
list.clear();
```

</div>
<div>

```java
import java.util.List;
import java.util.ArrayList;

java.util.List<String> list = new java.util.ArrayList<String>();
list.add("an object");
list.add("another object");

System.out.println("second element of the list: " + list.get(1));
list.clear();
```

</div>
</div>
