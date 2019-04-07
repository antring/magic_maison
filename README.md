# magic_maison
A backend playground


## Usage

### List all categories

### List all links

### Add new category
**Definition**
`POST /category/new`

**Arguments**
- `Name:string` a public description of the category

**Response**
- `201 Created` on success

### Add new link
**Definition**

`POST /link/new`

**Arguments**
- `"Name":string` a public name for the link
- `"URL":string` the link the user will be sent to

**Response**
- `201 Created` on success

```json
{
  "name": "Google",
  "url": "www.google.com"
}
```