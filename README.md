# Receiving Api Posts

## Objectives

  * Understand how params comes in from POST requests
  * Use those params to create resources

## Outline

  * "What if we want to modify the post create form to not require a refresh"
  * we need to send a POST. Turns out it's not really any different than what the form is doing.
  * Show them in jQuery how to do the POST
  * Comes in as the `params`
  * What should the response be? Well what do we want to show the user after they hit submit? We want to show the post! So let's make the response be just the post that was created
  * so let's use our AMS post serializer to respond with the post that was created
  * status code 201
  * Render the post in jQuery
