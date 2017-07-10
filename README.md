# \<dory-layout\>

## Example
```html
<dory-layout>
    <div slot="top-sidebar">
        <h1>Your Company Name</h1>
    </div>
    <div slot="title">
        <h1>Your Application Name</h1>
    </div>
    <div slot="content">
        Your content
    </div>
</dory-layout>
```

## Styling

```
--toolbar-height
--sidebar-background-color
--logo-background-color
--background-color
```

## Slots available

Name        |   Description
---         |    ---
`title`     |    Content displayed in the top bar, centered
`top-sidebar`   |   Content displayed in the top-left corner
`sidebar`   |   Content displayed in the sidebar (positioned to the left)
`content`   |   Main content