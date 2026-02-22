# Layouts

Application layout wrappers.

Purpose:
- Define page structure (header, footer, sidebar, etc.)
- Wrap pages with consistent UI

Rules:
- Layouts should handle structure, not business logic.
- Keep them reusable.
- Avoid API calls here.

Examples:
- MainLayout.jsx
- DashboardLayout.jsx

Typical pattern:

<MainLayout>
  <PageContent />
</MainLayout>