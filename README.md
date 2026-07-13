# Tools

Some useful tools collected in one repository.

## Projects

| Tool | Description | Path |
| --- | --- | --- |
| Local Resume Template Tool | A local-first resume editor with templates, themes, JSON import/export, and print-to-PDF support. | [`tools/resume-template-tool`](tools/resume-template-tool) |

## Repository Structure

```text
.
├── tools/
│   └── resume-template-tool/
├── LICENSE
├── README.md
└── package.json
```

Each tool should live in its own folder under `tools/` and include its own `README.md`.

## Development

Run all available checks from the repository root:

```bash
npm test
```

Run the resume tool locally:

```bash
npm run resume:serve
```

Then open:

```text
http://localhost:8765/
```

## License

MIT
