# tllester-fd

Hugo static-generated website that is pre-populated with migrated content (posts, pages, images, files, etc..) from three individual Wordpress blogs, all three originally located under the domain `artistsafety.net`.

## Running Pagefind

`alias hs='rm -rf public && npx -y pagefind --site public --serve`

`npm_config_yes=true npx pagefind --site "public" --output-subdir ../static/pagefind`

```bash
npm_config_yes=true npx pagefind --site "public" --output-subdir ../static/pagefind
hugo server
```
