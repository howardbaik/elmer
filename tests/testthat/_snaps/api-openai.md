# default model is reported

    Code
      . <- new_chat_openai()$chat("Hi")
    Message
      Using model = "gpt-4o-mini".

# can make an async tool call

    Code
      chat$chat("Great. Do it again.")
    Condition
      Error in `FUN()`:
      ! Can't use async tools with `$chat()` or `$stream()`.
      i Async tools are supported, but you must use `$chat_async()` or `$stream_async()`.

