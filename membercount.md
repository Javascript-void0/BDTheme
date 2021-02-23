# MemberCount Transparent Background

### Download MemberCount [Here](https://github.com/Arashiryuu/crap/tree/master/ToastIntegrated/MemberCount) from Arashiryuu's repo

### 1. Search for "Dark", or go to line 182 - `ctrl + f "dark"`

### 2. Add line `background: transparent !important;` under #MemberCount

### 3. Save :D

``` css
.theme-light #MemberCount {
	background: #f2f3f5;
}

.theme-dark #MemberCount {
	background: #2f3136;
}

#MemberCount {
background: transparent !important;    <= ADD SOMEWHERE IN HERE
position: absolute;
display: flex;
width: 240px;
text-align: center;
align-items: center;
justify-content: center;
padding: 0;
z-index: 5;
top: 0;
margin-top: -10px;
}
```
