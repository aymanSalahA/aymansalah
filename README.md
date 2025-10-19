## TODOS :

1. Add another Gdrive Download link , not flow cv

---

### How to Add a New Item to the Portfolio Page

1. **Check if there is a category `<li>` item with class `fillter-btn` or create it**
   This is for filtering / category. If a filter button for your category doesn’t exist, add a new `<li class="fillter-btn">` for it.

2. **Create a new preview `<div>` item with class `isotop-item`**

    - Assign it the corresponding `fillter-btn` category class.
    - Update the `href` of its link to point to the new modal.
    - Ensure the two IDs (in the preview item and the modal link) are consistent and unique.

3. **Copy a modal from the bottom and change its ID**
    - Duplicate an existing modal block.
    - Change **only** the modal’s `id` to match the `href` from Step 2.
    - Do **not** edit anything inside the modal—only update its content, metadata, links, etc., as needed.

---
