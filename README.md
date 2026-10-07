# Awesome WorkflowFiesta Templates

A collection of ready-to-use workflow templates for WorkflowFiesta.

## Templates

| Category | Template | What it does |
|---|---|---|
| Monitoring | [Website uptime monitor](monitoring/website-uptime-monitor.yaml) | Checks a URL every 5 minutes and sends a push alert (ntfy, Slack, Discord or email) when it is down. |

Templates are grouped in folders by category. Each file explains its setup (variables, credentials) in the comments at the top.

## Usage

1. Open a workflow in WorkflowFiesta, then choose **⋯ → Import from URL**.
2. Paste the template's **raw** URL, e.g.
   `https://raw.githubusercontent.com/<org>/awesome-workflowfiesta-templates/main/monitoring/website-uptime-monitor.yaml`
   (the normal `github.com/.../blob/...` page is HTML and will be rejected).
3. Follow the setup notes at the top of the template.

You can also copy the YAML into the workflow's YAML editor.

## Contributing

Open a pull request to add or improve a template. Put it in a category folder and add a row to the table above.
