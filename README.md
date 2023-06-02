# Resend with Supabase Edge Functions

This example shows how to use Resend with [Supabase Edge Functions](https://supabase.com/docs/guides/functions).

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