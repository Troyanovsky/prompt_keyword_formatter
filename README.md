# Prompt Keyword Formatter

A web-based tool that helps you manage and format text with customizable keywords and replacements. Perfect for template management, text preprocessing, and quick text substitutions.

## Features

- 🔄 Real-time keyword substitution
- 💾 Local storage for keyword persistence
- 📝 XML formatting support
- 🔍 Intelligent keyword suggestions
- ⌨️ Auto-completion for keywords
- 📤 Export/Import keyword configurations
- 📋 One-click copy to clipboard

## Use Cases

### SQL Development with LLMs
- Store complex table definitions as keywords (e.g., `@users_table`)
- Quickly paste table schemas into LLM prompts for SQL query generation
- Maintain consistency across multiple queries by using the same table definitions

### Template Management
- Save frequently used code snippets or boilerplate text
- Create standardized response templates for customer service
- Store API documentation templates

### Documentation
- Maintain consistent terminology across technical documents
- Quick insertion of complex technical specifications
- Standardize product descriptions or feature explanations

### Prompt Engineering
- Store and reuse effective prompt components
- Maintain a library of system instructions for different LLM use cases
- Quick assembly of complex prompts from pre-defined building blocks

## How to Use

1. **Add Keywords**
   - Use the "Add Keyword" button to create new keyword-replacement pairs
   - Enter your keyword and its corresponding replacement text
   - All keywords are automatically saved to local storage

2. **Format Text**
   - Type `@` followed by your keyword in the input field
   - Use the auto-suggestion feature to quickly insert keywords
   - Click "Format Prompt" to replace all keywords with their corresponding text

3. **XML Support**
   - Enable XML formatting to automatically close XML tags
   - When you type `>`, the corresponding closing tag will be inserted

4. **Import/Export**
   - Export your keyword configurations to share with others
   - Import keyword configurations from JSON files
   - Merged import support for combining keyword sets

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/Troyanovsky/prompt_keyword_formatter.git
```

2. Open `index.html` in your web browser

No additional setup or dependencies installation required! The project uses CDN-hosted Vue.js and Tailwind CSS.

## Technologies Used

- Vue.js 3
- Tailwind CSS
- HTML5
- JavaScript

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.
