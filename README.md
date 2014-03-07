# OmniAuth Moves

This is the OmniAuth strategy for authenticating to the Moves site. To
use it, you'll need to sign up for an OAuth2 Application ID and Secret
on the [Moves Site](https://dev.moves-app.com/).

## Basic Usage

    use OmniAuth::Builder do
      provider :moves, ENV['MOVES_APP_ID'], ENV['MOVES_APP_SECRET']
    end

## License

MIT