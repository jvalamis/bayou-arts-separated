# Cursor Prompt - Eddie Site

## You are in an EDDIE SITE repo (REPO_KIND: SITE).

### ALLOWED ACTIVITIES:
- ✅ **Visual polish ONLY**: theme, responsive scaffold, section widgets, routing glue
- ✅ **Pages-compatible paths** (Uri.base.resolve), hash routing/404 redirect
- ✅ **Pages workflow YAML** (build with --base-href /<REPO_NAME>/)
- ✅ **Assets/content/content.json** and images
- ✅ **UI/UX improvements** and responsive design
- ✅ **Accessibility enhancements** and performance optimizations

### FORBIDDEN ACTIVITIES:
- ❌ **Extractor/normalizer/templates** code
- ❌ **Adding new section types** (update generator+renderer instead)
- ❌ **Editing eddie_renderer source** (it is a dependency)
- ❌ **Changing content.json structure** (use generator for that)
- ❌ **Adding generator-specific files**

### PRIMARY GOALS:
- **Enforce Material 3 tokens**; no hardcoded colors
- **Max-width ~1200**, responsive padding (16/24/32), nav by breakpoint
- **Hero w/ rounded corners + gradient**; 24–32px section rhythm
- **A11y ≥ 90, Perf ≥ 90** (Lighthouse)

### KEY FILES:
- `lib/main.dart` - App entry point and routing
- `content.json` - Site content (DO NOT edit structure)
- `pubspec.yaml` - Dependencies (eddie_renderer via git)
- `.github/workflows/` - Pages deployment and quality gates
- `web/` - Web-specific assets and configuration

### COMMIT PREFIXES:
- `[SITE]` for site polish changes
- `[UI]` for visual improvements
- `[A11Y]` for accessibility fixes
- `[PERF]` for performance optimizations

**Remember: You are polishing the PRESENTATION of content, not changing the content structure or generator logic.**
