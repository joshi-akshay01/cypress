# cypress

SET CYPRESS_API_URL=http://localhost:1234/
npx cy2 run --record --key XXX --parallel --ci-build-id `date +%s`



Or

# run in each terminal
CYPRESS_API_URL="http://localhost:1234/" npx cy2 run --parallel --record --key somekey --ci-build-id hello-cypress

