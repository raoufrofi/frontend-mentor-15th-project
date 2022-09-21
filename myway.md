# Body contain main
```css
width: 100%;
min-height: 100vh;
```

**main** contain header
```css
width: min(380px, 85%);
display: grid;
gap: u.em(120);

```

## 1. header

contain **navbar**, **ul** and **figure**

### 1. header > navbar

img **logo** and **link**
<br>
```css
display: flex;
justify-content: space-between;
align-items: center;
```

### 2. header > div 
```css
display: grid;
gap: u.em(50);
```

### 1. ul

contain **h1**, **p** and **link**  
```css
display: grid;
gap: u.em(20);
```

### 2. figure
contain **img**


## 2. main > article 
contain 3 sections


### article > section
figure will contain img <br>
article will contain <br>
h2, and p
```css
display: grid;
gap: u.em();
```


## 3. main > Footer
