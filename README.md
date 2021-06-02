# lua-web-api-luarocks-nginx-postgres-post

## Description
Embedded lua in nginx config file
with JSON support. Allows for get
and post actions. Writes data to database.

## Tech stack
- lua
  - reqargs
- nginx

## Docker stack
- openresty/openresty:alpine

## To run
`sudo ./install.sh -u`
- POST curl -H "Content-Type: application/json" -X POST -d '{"some":"arbitrary","json": {"password":"xyz"}}' localhost:8000/

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://ketzacoatl.github.io/posts/2017-03-02-lua-and-openresty-hello-world-examples.html
