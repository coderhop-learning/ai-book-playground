# AI for Developers: playground

- `llmkit.py`: the book's offline toolkit (toy tokenizer, TinyLM, toy embeddings, the DocsPilot
  sample company, `FakeAnthropic`, and `mock_api()`, a local mock of the Messages API).
- `docs/`: DocsPilot's sample docs. `prompts/`, `evals/`: the prompt file and eval set.
- The other `.py` files are the modules the chapters build, exactly as shown in the book.
- `reference/`: Java versions of key classes, for reading.

Run `python llmkit.py serve` and export the printed variables to run the SDK examples without a key.
See playground-howto.html in the book for details.
