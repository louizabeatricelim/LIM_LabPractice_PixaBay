# LIM_LabPractice_PixaBay

## API Key

Copy your API key from your Pixabay account page. You will use this key in every request below.

<img width="641" height="119" alt="Pixabay API Key" src="https://github.com/user-attachments/assets/951937f8-d40b-42c1-b9ee-fed3a7b8bcce" />

> API Key: `57360554-9f0dff5cabdf74fc41952eb8d`

---

## Challenge 1: Rocket Launch (Video)

Build a request using these parameters, then document the request and the response.

### Parameters

| Parameter        | Value         |
| ---------------- | ------------- |
| Search Term      | Rocket Launch |
| Data Type        | Video         |
| Category         | Science       |
| Editor's Choice  | Yes           |
| Results Per Page | 3             |

### What to Submit

#### 1. Full API Request URL

```text
https://pixabay.com/api/videos/?key=YOUR_API_KEY&q=Rocket+Launch&category=science&editors_choice=true&per_page=3
```

#### 2. API Response

The response information returned by the API:

<img width="1905" height="584" alt="Pixabay API Response" src="https://github.com/user-attachments/assets/3aef21eb-d4d3-453f-b039-f6c8f2227279" />

---

## Challenge 2: Basketball (Video)

Build a request using these parameters, then document the request and the response.

### Parameters

| Parameter        | Value      |
| ---------------- | ---------- |
| Search Term      | Basketball |
| Data Type        | Video      |
| Category         | Sports     |
| Order            | Latest     |
| Results Per Page | 3          |

### What to Submit

#### 1. Full API Request URL

```text
https://pixabay.com/api/videos/?key=YOUR_API_KEY&q=Basketball&category=sports&order=latest&per_page=3
```

#### 2. API Response

The response information returned by the API:

<img width="1917" height="488" alt="Pixabay API Response" src="https://github.com/user-attachments/assets/2a080b28-b0f1-4ef8-8926-844b9dc3d073" />

---

## Challenge 3: Forest (Video)

This challenge asks for the request in a slightly different form. A request URL is the complete web address you send, including your search term and every filter. Query parameters are the individual pieces, such as the search term or the category, that get combined to build that URL. Listing them separately shows you understand each piece on its own, not just the finished address.

### Parameters

| Parameter        | Value      |
| ---------------- | ---------- |
| Search Term      | Forest     |
| Data Type        | Video      |
| Category         | Background |
| Editor's Choice  | Yes        |
| Order            | Latest     |
| Results Per Page | 3          |

### What to Submit

#### 1. Individual Request Query Parameters

List the query parameters used, one by one, with their values.

```text
key = YOUR_API_KEY
q = Forest
category = background
editors_choice = true
order = latest
per_page = 3
```

#### 2. API Request URL

```text
https://pixabay.com/api/videos/?key=YOUR_API_KEY&q=Forest&category=background&editors_choice=true&order=latest&per_page=3
```

#### 3. API Response

The response information returned by the API:

<img width="1253" height="290" alt="Pixabay API Response" src="https://github.com/user-attachments/assets/42917ad4-a835-4413-8459-38151e8569fb" />

---

## Challenge 4: Road Forest (Photo)

Build a request using these parameters, then document the request and the response.

### Parameters

| Parameter        | Value       |
| ---------------- | ----------- |
| Search Term      | Road Forest |
| Image Type       | Photo       |
| Category         | Nature      |
| Editor's Choice  | Yes         |
| Results Per Page | 3           |

### What to Submit

#### 1. Full API Request URL

```text
https://pixabay.com/api/?key=YOUR_API_KEY&q=Road+Forest&image_type=photo&category=nature&editors_choice=true&per_page=3
```

#### 2. API Response

The response information returned by the API.

JSON responses can be long, so only include the first 30 lines.

<img width="1892" height="408" alt="Pixabay API Response" src="https://github.com/user-attachments/assets/6b9bac99-c831-45d3-afca-5aed143b2d3d" />
