# Ruby on Rails - How to create Like buttons with Turbo Streams

This is going to be a simple tutorial on creating like buttons with turbo streams.

### Prerequisites...

- A basic understanding of Ruby on Rails
- Devise to model users that are logged in or not (for this example, a user must be logged in to like posts)

## Step 1: Create a User model with Devise

The reason we need a User modeled with Devise is because they provide a `current_user` method that tracks which user is in session when interacting with out app. If you already have devise (or an alternative way to track a `current_user` in session), you can go ahead and skip this step.

Otherwise, check out [Devise's documentation](https://github.com/heartcombo/devise#getting-started) on how to get started.
