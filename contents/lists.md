---
description: 'Lists are continuous, vertical indexes of text or images.'
---

# Lists

![Lists are continuous, vertical indexes of text or images.](../.gitbook/assets/group-22-copy-3.png)

## Anatomy

### 1. Definition

![](../.gitbook/assets/group-22-copy-4.png)

1. List : 리스트는 vertical index를 일컫는다.
2. Row : 리스트의 기본단위는 행이며, 행들이 모여 리스트가 된다.
3. List item content : 하기에서 설



### 2. Content Types

![](../.gitbook/assets/group-28.png)

1. Supporting visuals : Avatar, Thumbnail
2. Primary text : Title with secondary text
3. List control: Select, edit \(delete and reorder\), collapsable
4. Metadata: Text, informative visuals







## Types

**리스트는 다음과 같은 기준으로 타입을 정의할 수 있다.**

| Type | Line | Control | State |
| :--- | :--- | :--- | :--- |
| Avatar with text | One-line | Select | Normal |
| Avatar with text & thumbnail | Two-line | Edit | Selected |
| Thumbnail with text | Three-line | collapsable | Unread |
| Thumbnail with text including metadata |  | CTA |  |
| Text only |  |  |  |

### 

### 1. Avatar with text

![](../.gitbook/assets/group-59.png)

{% tabs %}
{% tab title="Dev Guide" %}
```text
This is dummy

.Item-area {
  width: 339px;
  height: 60px;
  background-color: rgba(255, 255, 255, 0);
} 
.Figure-circle----Primary {
  width: 60px;
  height: 60px;
  opacity: 0.08;
}
.List-Content {
  width: 265px;
  height: 22px;
  font-family: PingFangTC;
  font-size: 15px;
  font-weight: 500;
  font-style: normal;
  font-stretch: normal;
  line-height: 1.47;
  letter-spacing: -0.4px;
  color: var(--black);
```
{% endtab %}

{% tab title="Used in" %}
![](../.gitbook/assets/artboard-copy.png)

| Features | Page name |
| :--- | :--- |
| CP-Module | See More Page Sample |
| CP-Module | Fold Page Sample |
{% endtab %}
{% endtabs %}

### 

### 2. Avatar with text with thumbnail

![](../.gitbook/assets/group-60.png)

{% tabs %}
{% tab title="Dev Guide" %}
```text
This is dummy

.Item-area {
  width: 339px;
  height: 60px;
  background-color: rgba(255, 255, 255, 0);
} 
.Figure-circle----Primary {
  width: 60px;
  height: 60px;
  opacity: 0.08;
}
```
{% endtab %}

{% tab title="Used in" %}
![](../.gitbook/assets/artboard-copy-2.png)

| Features | Page name |
| :--- | :--- |
| UGC | Buzz Notification Page Sample |
{% endtab %}
{% endtabs %}

### 

### 3. Thumbnail with text

![](../.gitbook/assets/group-61.png)

{% tabs %}
{% tab title="Dev Guide" %}
```text
This is dummy

.Item-area {
  width: 339px;
  height: 60px;
  background-color: rgba(255, 255, 255, 0);
} 
.Figure-circle----Primary {
  width: 60px;
  height: 60px;
  opacity: 0.08;
}
```
{% endtab %}

{% tab title="Used in" %}
![](../.gitbook/assets/artboard-copy-3.png)

| Features | Page name |
| :--- | :--- |
| Today | Channel Page Sample |
|  | End Sample - Channel 1-2 |
| Movie |  |
| UGC |  |
| CP-Module | See More Page Sample |
| Election |  |
{% endtab %}
{% endtabs %}





### 4. Thumbnail with text including metadata

![](../.gitbook/assets/group-61.png)

{% tabs %}
{% tab title="Dev Guide" %}

{% endtab %}

{% tab title="Used in" %}

{% endtab %}
{% endtabs %}





### 5. Text only

![](../.gitbook/assets/group-55.png)

{% tabs %}
{% tab title="Dev Guide" %}
```text
This is dummy

/* Hint text */
font-family: Helvetica;
font-weight: regular;
font-size: 11px;
color: $gray50;
margin-top : 5px;

/* Error hint text */
font-weight: bold;
color: $red50;

/* Link/action text */
font-weight: bold;
color: $blue50;

/* Disabled */
color: $gray40;
```
{% endtab %}

{% tab title="Used in" %}
![](../.gitbook/assets/artboard%20%281%29.png)
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Related article : [**Dialog**](../foundation/communication/dialog.md)↗ , [**Menu**](menu.md)\*\*\*\*↗
{% endhint %}





