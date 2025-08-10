
### Reflection Loop Pattern

This pattern enables the Agent to **reflect on its own generated output**, providing feedback to progressively improve the final result.
And guess what? — this reflection mechanism can be as simple as a **loop**.

The **reflection loop** follows four main steps:

1. **Generation** – The LLM creates an initial output.
2. **Reflection** – The LLM reviews the output, identifies errors or improvements.
3. **Correction** – The feedback is applied to adjust the original output.
4. **Iteration** – The process repeats with the improved version.

**Example:**
Suppose the LLM writes an article on LangGraph but includes the wrong date.
In the reflection step, the LLM flags the incorrect date and suggests the correct one.
This correction is fed back into the generation step, producing a new article with the updated date.
The loop continues until there are no more corrections.

---

**When to Stop the Loop?**
Two common stopping criteria are:

* **Fixed iterations** – Stop after a set number of loops.
* **Stop sequence** – End when the LLM outputs a predefined phrase (e.g., `"OK"`, `"Correct"`), indicating the result is satisfactory.

---