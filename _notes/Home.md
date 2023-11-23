---
obsidianUIMode: preview
---

| Headspace        | Orienting Lens | Intention     | Organizing Principle | Underlying Benefit | Guiding Question              |
| ------------ | -------------- | ------------- | -------------------- | ------------------ | ----------------------------- |
| **Atlas**    | Knowledge      | To Understand | Relatedness / Space                | Learn / Remember             | _Where would you like to go?_ |
| **Calendar** | Time           | To Focus      | Time                 | Remember / Reflect          | _What's on your mind?_        |
| **Efforts**  | Action         | To Act        | Importance           | Create             | _What can you work on?_       |

> [!Map]- # Atlas
> > *Where would you like to go?*

> [!Calendar]- # Calendar
> > *What's on your mind?* 

> [!Training]- # Efforts
> > *What can you work on?* 
> 
> > [!Box]+ ### 🔥 On
> > ``` dataview
> > TABLE WITHOUT ID
>  > file.link as "",
>  > rank as "Rank"
> > FROM "Efforts/On"
> > SORT rank desc
> > ```
> 
> > [!Box]+ ### ♻️ Ongoing
> > ``` dataview
> > TABLE WITHOUT ID
> > file.link as "",
> > rank as "Rank"
> > FROM "Efforts/Ongoing"
> > SORT rank desc
> > ```
> 
> > [!Box]- ### 〰️ Simmering
> > ``` dataview
> > TABLE WITHOUT ID
> > file.link as "",
> > rank as "Rank"
> > FROM "Efforts/Simmering"
> > SORT rank desc
> > ```

