# Admin Dashboard

![Image of an admin dashboard web page.](assets/images/dashboard-project.png)

This web page is an implementation based on the above UI design mock-up.

<!-- Site is live [here](https://junyuhuang.github.io/top-admin-dashboard/). -->

## Page Layout Planning

### Page Element Hierarchy

- `.container`
  - `.sidebar`
    - `.logo-container`
      - `img` (dashboard icon)
      - `h1`
    - `.link` x 6
      - `img`
      - `a`
    - `.link` x 3
      - `img`
      - `a`
  - `.header`
    - `.row-1`
      - `form`
        - `img` (magnifying glass icon)
        - `input` (search box)
      - `img` (bell icon)
      - `img` (cat avatar image)
      - `p` or `a`
    - `.row-2`
      - `.profile-card`
        - `img` (cat avatar medium image)
        - `div`
          - `p`
          - `h2`
      - `.button` x 3 (new, upload, share buttons)
  - `.main-content`
    - `.projects`
      - `h3`
      - `.projects-container`
        - `.card` x 6
          - `h4`
          - `p`
          - `div`
            - `img` x 3 (star, eye, source icons)
    - `.announcements`
      - `h3`
      - `.announcements-container`
        - `div` x 3
          - `h4`
          - `p`
          - `br`
    - `.trending`
      - `h3`
      - `.trending-container`
        - `.trending-card` x 4
          - `img` (small avatar image)
          - `div`
            - `p`
            - `p`

### Page Layout Notes

- `.container`:
  - 2 Grid columns
  - 2nd column is ~3.75x the size of 1st column
- `.sidebar`:
  - 606px width
  - 46px padding horiz. / vert.

## TODOs

- [x] Set up project boilerplate assets, files, and code
- [x] Finish page element hierarchy planning
- [ ] Finish page layout notes
- [x] Copy text content from UI design image to `assets/content.txt`
- [x] Complete sidebar component
- [ ] Complete header top row (with search box) component
- [x] Complete header bottom row (with buttons) component
- [x] Complete main-content projects section component
- [x] Complete main-content announcements section content
- [x] Complete main-content trending section content
- [ ] Fix extra height issue with grid layout (related to top and bottom padding in `.main-content` element)

## Assets To Download

- [x] Project UI Design Image
- [x] Roboto Regular, Roboto Medium, Roboto Bold fonts
- [x] Cat Avatar Image
- [x] Dog Avatar Image
- [x] Spiderman with Headphones Avatar Image
- [x] Penguin with beanie and scarf Avatar Image
- [x] Dashboard Logo Icon
- [x] Home / House Icon
- [x] Profile / Card Icon
- [x] Messages / Chat Icon
- [x] History / Clock Icon
- [x] Tasks / Pages Icon
- [x] Community / People Icon
- [x] Settings / Cog Icon
- [x] Support / Question Mark Box Icon
- [x] Privacy / Shield Icon
- [x] Favorite / Star+ Icon
- [x] View / Eye+ Icon
- [x] Source Icon
- [x] Search / Magnifying Glass Icon
- [x] Bell / Notification Icon

## Stuff To Configure

- [x] Setup Tailwind config with colours and images
