# Package Repository Agent Guide

This repository is public. Apply these rules to comments, documentation,
examples, agent instructions, templates, and generated text:

- Do not add internal operational instructions or infrastructure details.
- Exclude credential identifiers, credential storage locations, private hostnames,
  runner paths, SSH provisioning steps, and internal release or recovery procedures.
- Keep internal runbooks with their owning private repository.
- Keep public installation and signature verification instructions that users
  need. Use generic examples for infrastructure details.
- Preserve package metadata, signatures, and executable behavior when you remove
  internal prose.
- Review changed text for internal details before you complete the task.
- Check generated and copied text. Correct the source and its published copy
  together.
- Do not repeat removed internal identifiers as examples of prohibited content.

The README source is `packaging/repositories/README.md` in `verdictan/verdictan`.
Update that source with this README so publication does not restore removed text.
