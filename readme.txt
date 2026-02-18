# add curl

apk add --no-cache curl


# add data
curl -X POST localhost:4000/posts --header "Content-Type: application/json" --data-raw '{"title": "The first post in docker"}' 


hosts file
127.0.0.1 posts.com 


navigate to:
posts.com/posts

# run one by one. 
curl -X POST posts.com/posts --header "Content-Type: application/json" --data-raw '{"title": "The first post in docker"}' 
curl -X POST posts.com/posts --header "Content-Type: application/json" --data-raw '{"title": "The second post in docker"}' 
curl -X POST posts.com/posts --header "Content-Type: application/json" --data-raw '{"title": "Another post in docker"}' 