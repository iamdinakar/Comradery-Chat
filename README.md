This is the real time chat repository for Comradery. You should change `API_PRODUCTION_URL` and `API_DEV_URL` in `index.js` to point to the backend Comradery servers you've set up.

This should be fairly easy to run locally by using `yarn install` and then `node index.js`.

This should be fairly easy to setup on Heroku, however you must set it up to [share the Redis instance with the backend](https://devcenter.heroku.com/articles/heroku-redis#:~:text=You%20can%20share%20one%20Heroku%20Redis%20between%20multiple%20applications.&text=If%20you%20already%20have%20an,with%20the%20config%20var%20REDIS_URL%20.). You must also set `IN_HEROKU` to 1 in the Heroku Config Vars.
