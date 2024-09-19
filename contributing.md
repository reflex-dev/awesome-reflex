# Contributor Guide: Adding Resources to Awesome Reflex

Thank you for your interest in contributing to our Awesome List for Reflex! This guide will walk you through the process of adding new resources to our repository.

## Steps to Contribute

### 1. Fork the Repository

- Go to our GitHub repository: [https://github.com/reflex-dev/awesome-reflex](https://github.com/reflex-dev/awesome-reflex)
- Click the "Fork" button in the top-right corner to create a copy in your account.

### 2. Clone Your Fork

```bash
git clone https://github.com/[Your-Username]/awesome-reflex.git
cd awesome-reflex
```

### 3. Create a New Branch

```bash
git checkout -b add-new-resource
```

### 4. Add Your Resource

1. Open the `README.md` file in a text editor.
1. Find the appropriate section for your resource.
1. Add your resource using this format:

```markdown
Resource Name - Brief description of the resource.
```

Save the file.

### 5. Commit Your Changes

```bash
git add README.md
git commit -m "Add [Resource Name] to [Section Name]"
```

### 6. Push Your Changes

```bash
git push origin add-new-resource
```

### 7. Open a Pull Request

1. Go to your fork on GitHub.
1. Click "Compare & pull request" next to your `add-new-resource` branch.
1. Ensure the "base repository" is set to `reflex-dev/awesome-reflex` and "base" is set to `main`.
1. Fill in the pull request title and description.
1. Click "Create pull request."

### Guidelines for Adding Resources

- Ensure the resource is directly related to Reflex.
- Check that the resource hasn't already been added.
- Provide a concise, informative description.
- Place the resource in the appropriate section.
- Maintain alphabetical order within sections.

### Need Help?

If you're new to GitHub or need assistance, don't hesitate to ask for help in the pull request comments or open an issue in the repository.
