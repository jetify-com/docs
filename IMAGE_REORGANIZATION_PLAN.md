# Image Reorganization Plan

## Current Issues
1. **Random hash suffixes**: All images have hash strings like `-8852415bc8ed8b6677a0d3e8b36a271a`
2. **Nested "docs/assets/images" paths**: Redundant nesting within already organized folders
3. **Not SEO-friendly**: Names don't always reflect content clearly
4. **Not colocated**: All images in centralized folder instead of with their content

## Key Concept: Colocation vs Shared

### Colocated Images (27 images)
- **File location**: Inside the `docs/` folder structure alongside the MDX file
- **Example file path**: `docs/cloud/dashboard/inviting-members/members-tab-navigation.png`
- **Reference options**:
  - Absolute: `/docs/cloud/dashboard/inviting-members/members-tab-navigation.png`
  - Relative: `./members-tab-navigation.png` (preferred for colocated files)

### Shared Images (2 badges)
- **File location**: Inside the `images/` folder (for reusable assets)
- **Example file path**: `images/devbox/badges/devbox-badge-galaxy.svg`
- **Reference**: `/images/devbox/badges/devbox-badge-galaxy.svg`

## Reorganization Strategy

### Cloud Dashboard Images

#### `/images/docs/cloud/dashboard/docs/assets/images/jetify_cloud_dashboard-8852415bc8ed8b6677a0d3e8b36a271a.jpeg`
- **Used in**: `docs/cloud/dashboard/index.mdx`
- **Alt text**: "Jetify Dashboard"
- **Proposed name**: `jetify-cloud-dashboard-overview.jpeg`
- **Proposed location**: `docs/cloud/dashboard/jetify-cloud-dashboard-overview.jpeg` (colocated)
- **New reference**: `./jetify-cloud-dashboard-overview.jpeg` or `/docs/cloud/dashboard/jetify-cloud-dashboard-overview.jpeg`

#### Creating Your Team Section

##### `/images/docs/cloud/dashboard/creating-your-team/docs/assets/images/create_team_form-dc9bb471dbb0a60cb2da2c2147bf7d8c.png`
- **Used in**: `docs/cloud/dashboard/creating-your-team/index.mdx`
- **Alt text**: "Create Team Form"
- **Proposed name**: `create-team-form.png`
- **Proposed location**: `docs/cloud/dashboard/creating-your-team/create-team-form.png` (colocated)
- **New reference**: `./create-team-form.png` or `/docs/cloud/dashboard/creating-your-team/create-team-form.png`

##### `/images/docs/cloud/dashboard/creating-your-team/docs/assets/images/team_selector-3878e484bde014913d146b6d0cc4a8e9.png`
- **Used in**: `docs/cloud/dashboard/creating-your-team/index.mdx`
- **Alt text**: "New Team"
- **Proposed name**: `team-selector-dropdown.png`
- **Proposed location**: `docs/cloud/dashboard/creating-your-team/team-selector-dropdown.png` (colocated)
- **New reference**: `./team-selector-dropdown.png` or `/docs/cloud/dashboard/creating-your-team/team-selector-dropdown.png`

#### Inviting Members Section

##### `/images/docs/cloud/dashboard/inviting-members/docs/assets/images/members_tab-40dac07b43ae1162fd178d9b38fa9b87.png`
- **Used in**: `docs/cloud/dashboard/inviting-members/index.mdx`
- **Alt text**: "Members Tab"
- **Proposed name**: `members-tab-navigation.png`
- **Proposed location**: `docs/cloud/dashboard/inviting-members/members-tab-navigation.png` (colocated)
- **New reference**: `./members-tab-navigation.png` or `/docs/cloud/dashboard/inviting-members/members-tab-navigation.png`

##### `/images/docs/cloud/dashboard/inviting-members/docs/assets/images/inviting_member-185c3642afb2ec95b3a0ea74d1fe4039.png`
- **Used in**: `docs/cloud/dashboard/inviting-members/index.mdx`
- **Alt text**: "Inviting a Member"
- **Proposed name**: `invite-member-form.png`
- **Proposed location**: `docs/cloud/dashboard/inviting-members/invite-member-form.png` (colocated)
- **New reference**: `./invite-member-form.png` or `/docs/cloud/dashboard/inviting-members/invite-member-form.png`

##### `/images/docs/cloud/dashboard/inviting-members/docs/assets/images/invited_member-b45b2434a407126d929bfb74a0023244.png`
- **Used in**: `docs/cloud/dashboard/inviting-members/index.mdx`
- **Alt text**: "Invited Member"
- **Proposed name**: `member-status-invited.png`
- **Proposed location**: `docs/cloud/dashboard/inviting-members/member-status-invited.png` (colocated)
- **New reference**: `./member-status-invited.png` or `/docs/cloud/dashboard/inviting-members/member-status-invited.png`

##### `/images/docs/cloud/dashboard/inviting-members/docs/assets/images/active_member-c43971cb25bcc844be7272904bdb435b.png`
- **Used in**: `docs/cloud/dashboard/inviting-members/index.mdx`
- **Alt text**: "Active Member"
- **Proposed name**: `member-status-active.png`
- **Proposed location**: `docs/cloud/dashboard/inviting-members/member-status-active.png` (colocated)
- **New reference**: `./member-status-active.png` or `/docs/cloud/dashboard/inviting-members/member-status-active.png`

##### `/images/docs/cloud/dashboard/inviting-members/docs/assets/images/delete_member-5a80c98ba2e46c130db5188428dd72ba.png`
- **Used in**: `docs/cloud/dashboard/inviting-members/index.mdx`
- **Alt text**: "Delete a member"
- **Proposed name**: `delete-member-action.png`
- **Proposed location**: `docs/cloud/dashboard/inviting-members/delete-member-action.png` (colocated)
- **New reference**: `./delete-member-action.png` or `/docs/cloud/dashboard/inviting-members/delete-member-action.png`

### Cloud Deploys Images

#### Setup Section

##### `/images/docs/cloud/deploys/setup/docs/assets/images/newproject-tworepos-98db61751c75634ba7446dc2a350e80e.png`
- **Used in**: `docs/cloud/deploys/setup/index.mdx`
- **Alt text**: "Select the Repo for your Jetify Project"
- **Proposed name**: `select-repository-for-project.png`
- **Proposed location**: `docs/cloud/deploys/setup/select-repository-for-project.png` (colocated)
- **New reference**: `./select-repository-for-project.png` or `/docs/cloud/deploys/setup/select-repository-for-project.png`

#### Monitoring Deploys Section

##### `/images/docs/cloud/deploys/monitoring-deploys/docs/assets/images/deploy-in-progress-a93eef4fa2c06b7e03a8a05726acc6af.png`
- **Used in**: `docs/cloud/deploys/monitoring-deploys/index.mdx`
- **Alt text**: "Build logs"
- **Proposed name**: `deployment-build-logs.png`
- **Proposed location**: `docs/cloud/deploys/monitoring-deploys/deployment-build-logs.png` (colocated)
- **New reference**: `./deployment-build-logs.png` or `/docs/cloud/deploys/monitoring-deploys/deployment-build-logs.png`

##### `/images/docs/cloud/deploys/monitoring-deploys/docs/assets/images/runtime-logs-983a71aca45444804d942ccf94496cd1.png`
- **Used in**: `docs/cloud/deploys/monitoring-deploys/index.mdx`
- **Alt text**: "Runtime Logs"
- **Proposed name**: `deployment-runtime-logs.png`
- **Proposed location**: `docs/cloud/deploys/monitoring-deploys/deployment-runtime-logs.png` (colocated)
- **New reference**: `./deployment-runtime-logs.png` or `/docs/cloud/deploys/monitoring-deploys/deployment-runtime-logs.png`

#### Custom Domains Section

##### `/images/docs/cloud/deploys/custom-domains/docs/assets/images/custom-domain-e02341c0d771b1f4d425f37a0caf9cc3.png`
- **Used in**: `docs/cloud/deploys/custom-domains/index.mdx`
- **Alt text**: "Custom Domain Section"
- **Proposed name**: `custom-domain-settings.png`
- **Proposed location**: `docs/cloud/deploys/custom-domains/custom-domain-settings.png` (colocated)
- **New reference**: `./custom-domain-settings.png` or `/docs/cloud/deploys/custom-domains/custom-domain-settings.png`

##### `/images/docs/cloud/deploys/custom-domains/docs/assets/images/custom-domain-unknown-541badd59754c21949c3b3dd79b759fa.png`
- **Used in**: `docs/cloud/deploys/custom-domains/index.mdx`
- **Alt text**: "Pending custom domain"
- **Proposed name**: `custom-domain-status-pending.png`
- **Proposed location**: `docs/cloud/deploys/custom-domains/custom-domain-status-pending.png` (colocated)
- **New reference**: `./custom-domain-status-pending.png` or `/docs/cloud/deploys/custom-domains/custom-domain-status-pending.png`

##### `/images/docs/cloud/deploys/custom-domains/docs/assets/images/custom-domain-issued-3776c9f34d10f487fe1bff26c65b105b.png`
- **Used in**: `docs/cloud/deploys/custom-domains/index.mdx`
- **Alt text**: "Custom Domain Issued"
- **Proposed name**: `custom-domain-status-issued.png`
- **Proposed location**: `docs/cloud/deploys/custom-domains/custom-domain-status-issued.png` (colocated)
- **New reference**: `./custom-domain-status-issued.png` or `/docs/cloud/deploys/custom-domains/custom-domain-status-issued.png`

#### Integrations - S3

##### `/images/docs/cloud/deploys/integrations/s3/docs/assets/images/s3-secrets-44f05d9135f9aac03817fad23a382fd8.png`
- **Used in**: `docs/cloud/deploys/integrations/s3/index.mdx`
- **Alt text**: "S3 Jetify Secrets"
- **Proposed name**: `s3-secrets-configuration.png`
- **Proposed location**: `docs/cloud/deploys/integrations/s3/s3-secrets-configuration.png` (colocated)
- **New reference**: `./s3-secrets-configuration.png` or `/docs/cloud/deploys/integrations/s3/s3-secrets-configuration.png`

#### Integrations - Supabase

##### `/images/docs/cloud/deploys/integrations/supabase/docs/assets/images/supabase-API-f40f4b71577eb6272448b379a96f800b.png`
- **Used in**: `docs/cloud/deploys/integrations/supabase/index.mdx`
- **Alt text**: "Supabase API UI"
- **Proposed name**: `supabase-api-settings.png`
- **Proposed location**: `docs/cloud/deploys/integrations/supabase/supabase-api-settings.png` (colocated)
- **New reference**: `./supabase-api-settings.png` or `/docs/cloud/deploys/integrations/supabase/supabase-api-settings.png`

##### `/images/docs/cloud/deploys/integrations/supabase/docs/assets/images/supabase-secrets-8bf8278bfacb052c766e14e6ab7e3859.png`
- **Used in**: `docs/cloud/deploys/integrations/supabase/index.mdx`
- **Alt text**: "Secrets set in the Jetify Cloud"
- **Proposed name**: `supabase-secrets-configuration.png`
- **Proposed location**: `docs/cloud/deploys/integrations/supabase/supabase-secrets-configuration.png` (colocated)
- **New reference**: `./supabase-secrets-configuration.png` or `/docs/cloud/deploys/integrations/supabase/supabase-secrets-configuration.png`

##### `/images/docs/cloud/deploys/integrations/supabase/docs/assets/images/connection_parameters-8998ee5136c176392f8132bbef76fe9c.png`
- **Used in**: `docs/cloud/deploys/integrations/supabase/index.mdx`
- **Alt text**: "Supabase Connection Parameters"
- **Proposed name**: `supabase-connection-parameters.png`
- **Proposed location**: `docs/cloud/deploys/integrations/supabase/supabase-connection-parameters.png` (colocated)
- **New reference**: `./supabase-connection-parameters.png` or `/docs/cloud/deploys/integrations/supabase/supabase-connection-parameters.png`

##### `/images/docs/cloud/deploys/integrations/supabase/docs/assets/images/postgres-secrets-6e3fb9b4ba5a504cf4a24e1175458c48.png`
- **Used in**: `docs/cloud/deploys/integrations/supabase/index.mdx`
- **Alt text**: "Postgres Secrets"
- **Proposed name**: `supabase-postgres-secrets.png`
- **Proposed location**: `docs/cloud/deploys/integrations/supabase/supabase-postgres-secrets.png` (colocated)
- **New reference**: `./supabase-postgres-secrets.png` or `/docs/cloud/deploys/integrations/supabase/supabase-postgres-secrets.png`

#### Integrations - Upstash

##### `/images/docs/cloud/deploys/integrations/upstash/docs/assets/images/upstash-1b2a0f7038b7b865caeff49d4fe1e750.png`
- **Used in**: `docs/cloud/deploys/integrations/upstash/index.mdx`
- **Alt text**: "Upstash Dashboard after clicking Create"
- **Proposed name**: `upstash-dashboard-create.png`
- **Proposed location**: `docs/cloud/deploys/integrations/upstash/upstash-dashboard-create.png` (colocated)
- **New reference**: `./upstash-dashboard-create.png` or `/docs/cloud/deploys/integrations/upstash/upstash-dashboard-create.png`

##### `/images/docs/cloud/deploys/integrations/upstash/docs/assets/images/upstash-secrets-8c63c8aa78f3246126a464ed4477dd7e.png`
- **Used in**: `docs/cloud/deploys/integrations/upstash/index.mdx`
- **Alt text**: "Secrets set in the Jetify Cloud"
- **Proposed name**: `upstash-secrets-configuration.png`
- **Proposed location**: `docs/cloud/deploys/integrations/upstash/upstash-secrets-configuration.png` (colocated)
- **New reference**: `./upstash-secrets-configuration.png` or `/docs/cloud/deploys/integrations/upstash/upstash-secrets-configuration.png`

### Cloud Secrets Images

#### Dashboard Secrets

##### `/images/docs/cloud/secrets/dashboard-secrets/docs/assets/images/secrets_tab-b1227831ec220ace5b4c0cb52bb2f046.png`
- **Used in**: `docs/cloud/secrets/dashboard-secrets/index.mdx`
- **Alt text**: "Jetify Dashboard Secrets Tab"
- **Proposed name**: `secrets-tab-navigation.png`
- **Proposed location**: `docs/cloud/secrets/dashboard-secrets/secrets-tab-navigation.png` (colocated)
- **New reference**: `./secrets-tab-navigation.png` or `/docs/cloud/secrets/dashboard-secrets/secrets-tab-navigation.png`

##### `/images/docs/cloud/secrets/dashboard-secrets/docs/assets/images/edit_secrets-d57474e57dc301f1b18cea20fd0dd9c9.png`
- **Used in**: `docs/cloud/secrets/dashboard-secrets/index.mdx`
- **Alt text**: "Editing Secrets"
- **Proposed name**: `edit-secrets-interface.png`
- **Proposed location**: `docs/cloud/secrets/dashboard-secrets/edit-secrets-interface.png` (colocated)
- **New reference**: `./edit-secrets-interface.png` or `/docs/cloud/secrets/dashboard-secrets/edit-secrets-interface.png`

#### Secrets CLI

##### `/images/docs/cloud/secrets/secrets-cli/docs/assets/images/jetify_auth-adff470443c8c0ee1c855227bbe35ef9.jpeg`
- **Used in**: `docs/cloud/secrets/secrets-cli/index.mdx`
- **Alt text**: "Auth Page"
- **Proposed name**: `jetify-authentication-page.jpeg`
- **Proposed location**: `docs/cloud/secrets/secrets-cli/jetify-authentication-page.jpeg` (colocated)
- **New reference**: `./jetify-authentication-page.jpeg` or `/docs/cloud/secrets/secrets-cli/jetify-authentication-page.jpeg`

### Devbox Images

#### Guides - Services

##### `/images/docs/devbox/guides/services/docs/assets/images/process-compose-tui-ea6c8521f9edc58340be82f160aa7da6.png`
- **Used in**: `docs/devbox/guides/services/index.mdx`
- **Alt text**: "Process Compose running in the foreground"
- **Proposed name**: `process-compose-tui-interface.png`
- **Proposed location**: `docs/devbox/guides/services/process-compose-tui-interface.png` (colocated)
- **New reference**: `./process-compose-tui-interface.png` or `/docs/devbox/guides/services/process-compose-tui-interface.png`

#### Quickstart - Badges (SHARED)

##### `/images/docs/devbox/quickstart/img/devbox/shield_galaxy.svg`
- **Used in**: `docs/devbox/quickstart/index.mdx`
- **Alt text**: "Built with Devbox"
- **Proposed name**: `devbox-badge-galaxy.svg`
- **Proposed location**: `images/devbox/badges/devbox-badge-galaxy.svg` (shared - could be reused)
- **New reference**: `/images/devbox/badges/devbox-badge-galaxy.svg`

##### `/images/docs/devbox/quickstart/img/devbox/shield_moon.svg`
- **Used in**: `docs/devbox/quickstart/index.mdx`
- **Alt text**: "Built with Devbox"
- **Proposed name**: `devbox-badge-moon.svg`
- **Proposed location**: `images/devbox/badges/devbox-badge-moon.svg` (shared - could be reused)
- **New reference**: `/images/devbox/badges/devbox-badge-moon.svg`

### TestPilot Images

##### `/images/testpilot/docs/getting-started/testpilot/docs/assets/images/test-output-page-f41cfad1fec38410ba5a455be8405998.png`
- **Used in**: `docs/testpilot/getting-started/testing-web-apps.mdx`
- **Alt text**: "Test Output Example"
- **Proposed name**: `testpilot-test-output-example.png`
- **Proposed location**: `docs/testpilot/getting-started/testpilot-test-output-example.png` (colocated)
- **New reference**: `./testpilot-test-output-example.png` or `/docs/testpilot/getting-started/testpilot-test-output-example.png`

## Summary of Changes

### Total Images: 29

### Colocation Strategy
- **Colocated (27 images)**: Images used in only one article should live next to that article
- **Shared (2 images)**: Devbox badges might be reused across documentation, keep in shared location

### New Structure Pattern

**Colocated images** (27 images in `docs/` folder):
```
docs/
├── cloud/
│   ├── dashboard/
│   │   ├── index.mdx
│   │   ├── jetify-cloud-dashboard-overview.jpeg
│   │   ├── creating-your-team/
│   │   │   ├── index.mdx
│   │   │   ├── create-team-form.png
│   │   │   └── team-selector-dropdown.png
│   │   └── inviting-members/
│   │       ├── index.mdx
│   │       ├── members-tab-navigation.png
│   │       ├── invite-member-form.png
│   │       ├── member-status-invited.png
│   │       ├── member-status-active.png
│   │       └── delete-member-action.png
│   ├── deploys/
│   │   ├── setup/
│   │   │   ├── index.mdx
│   │   │   └── select-repository-for-project.png
│   │   ├── monitoring-deploys/
│   │   │   ├── index.mdx
│   │   │   ├── deployment-build-logs.png
│   │   │   └── deployment-runtime-logs.png
│   │   ├── custom-domains/
│   │   │   ├── index.mdx
│   │   │   ├── custom-domain-settings.png
│   │   │   ├── custom-domain-status-pending.png
│   │   │   └── custom-domain-status-issued.png
│   │   └── integrations/
│   │       ├── s3/
│   │       │   ├── index.mdx
│   │       │   └── s3-secrets-configuration.png
│   │       ├── supabase/
│   │       │   ├── index.mdx
│   │       │   ├── supabase-api-settings.png
│   │       │   ├── supabase-secrets-configuration.png
│   │       │   ├── supabase-connection-parameters.png
│   │       │   └── supabase-postgres-secrets.png
│   │       └── upstash/
│   │           ├── index.mdx
│   │           ├── upstash-dashboard-create.png
│   │           └── upstash-secrets-configuration.png
│   └── secrets/
│       ├── dashboard-secrets/
│       │   ├── index.mdx
│       │   ├── secrets-tab-navigation.png
│       │   └── edit-secrets-interface.png
│       └── secrets-cli/
│           ├── index.mdx
│           └── jetify-authentication-page.jpeg
├── devbox/
│   └── guides/
│       └── services/
│           ├── index.mdx
│           └── process-compose-tui-interface.png
└── testpilot/
    └── getting-started/
        ├── testing-web-apps.mdx
        └── testpilot-test-output-example.png
```

**Shared images** (2 badges in `images/` folder):
```
images/
├── devbox/
│   └── badges/
│       ├── devbox-badge-galaxy.svg
│       └── devbox-badge-moon.svg
└── logo/                    # Existing logos (unchanged)
    ├── dark.svg
    └── light.svg
```

## SEO Benefits
1. ✅ **Descriptive keywords**: Every filename now contains relevant, searchable terms
2. ✅ **No random characters**: Removed all hash suffixes
3. ✅ **Hyphens for separation**: Following best practices for URL-friendly naming
4. ✅ **Concise paths**: Removed redundant "docs/assets/images" nesting
5. ✅ **Logical hierarchy**: Clear organization by product/feature area
6. ✅ **Context-rich names**: Image names describe what they show, not just generic names

## Next Steps
1. Create new directory structure
2. Copy and rename images to new locations
3. Update all MDX file references
4. Verify images render correctly
5. Delete old image files and directories
6. Commit changes
