# Organization Templates

## Workflow template

Workflow templates can be created by users with write access to the organization's public .github repository. These can then be used by organization members who have permission to create workflows.

Workflow templates created by users can only be used to create workflows in public repositories. Organizations using GitHub Enterprise Cloud can also use workflow templates to create workflows in private repositories.

## Metadata description

**name** - Required. The name of the workflow. This is displayed in the list of available workflows.

**description** - Required. The description of the workflow. This is displayed in the list of available workflows.

**iconName** - Optional. Specifies an icon for the workflow that is displayed in the list of workflows. iconName can one of the following types:

- An SVG file that is stored in the workflow-templates directory. To reference a file, the value must be the file name without the file extension. For example, an SVG file named example-icon.svg is referenced as example-icon.
- An icon from GitHub's set of Octicons. To reference an octicon, the value must be octicon <icon name>. For example, octicon smiley.

**categories** - Optional. Defines the categories that the workflow is shown under. You can use category names from the following lists:

- General category names from the starter-workflows repository.
- Linguist languages from the list in the linguist repository.
- Supported tech stacks from the list in the starter-workflows repository.

**filePatterns** - Optional. Allows the workflow to be used if the user's repository has a file in its root directory that matches a defined regular expression.
