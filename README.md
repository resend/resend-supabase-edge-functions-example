# Resend with Supabase Edge Functions

This example shows how to use Resend with [Supabase Edge Functions](https://supabase.com/docs/guides/functions).

## Prerequisites

To get the most out of this guide, you’ll need to:

* [Create an API key](https://resend.com/api-keys)
* [Verify your domain](https://resend.com/domains)

## Instructions

1. Make sure you have the latest version of the [Supabase CLI](https://supabase.com/docs/guides/cli#installation) installed.

2. Run function locally:

  ```sh
supabase functions start
supabase functions serve resend --no-verify-jwt
  ```

3. Deploy function to Supabase:

  ```sh
supabase functions deploy resend
  ```

## License

MIT License