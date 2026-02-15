# add curl

apk add --no-cache curl


# add data
curl -X POST localhost:4000/posts --header "Content-Type: application/json" --data-raw '{"title": "The first post in docker"}' 


