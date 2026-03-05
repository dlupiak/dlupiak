# Open Source Contribution Opportunities

Curated list of `good first issue` and `help wanted` issues matching my tech stack.

---

## .NET / C#

| Project | Issue | Difficulty |
|---|---|---|
| dotnet/efcore | [Support Half type in Sqlite](https://github.com/dotnet/efcore/issues/30931) | Easy |
| dotnet/efcore | [Support BigInteger, Int128 in Sqlite](https://github.com/dotnet/efcore/issues/30930) | Easy |
| dotnet/aspnetcore | [Skip SecurityScheme for AllowAnonymous](https://github.com/dotnet/aspnetcore/issues/61264) | Medium |
| dotnet/aspnetcore | [Pass css class to ValidationSummary `<ul>`](https://github.com/dotnet/aspnetcore/issues/43860) | Easy |
| dotnet/aspnetcore | [Add StringSyntax formats throughout codebase](https://github.com/dotnet/aspnetcore/issues/44535) | Easy |
| dotnet/runtime | [Unnecessary shr emitted for repeated multiplication](https://github.com/dotnet/runtime/issues/74020) | Medium |
| dotnet/aspnetcore | [Blazor DotNetStreamReference blob() method](https://github.com/dotnet/aspnetcore/issues/61826) | Medium |
| dotnet/aspnetcore | [AuthorizeView expose AuthorizeAsync results](https://github.com/dotnet/aspnetcore/issues/43959) | Medium |
| nunit/nunit | [Setting category for tests from TestFixtureSource](https://github.com/nunit/nunit/issues/3862) | Easy |

## TypeScript / React / Frontend

| Project | Issue | Difficulty |
|---|---|---|
| TanStack/query | [DevTools isolation issue](https://github.com/TanStack/query/issues/9681) | Medium |
| TanStack/query | [useQueries vs useQuery type checking for select](https://github.com/TanStack/query/issues/6556) | Medium |
| TanStack/form | [Docs guide for getting/setting field values](https://github.com/TanStack/form/issues/478) | Easy |
| storybookjs/storybook | [Tailwind 4 hover pseudo state compatibility](https://github.com/storybookjs/storybook/issues/32443) | Medium |
| storybookjs/storybook | [Broken types for useArgs generic](https://github.com/storybookjs/storybook/issues/25070) | Medium |
| microsoft/TypeScript | [Sort JSDoc param suggestions by position](https://github.com/microsoft/TypeScript/issues/20183) | Medium |
| microsoft/TypeScript | [Confusing error for this["XXX"] with missing key](https://github.com/microsoft/TypeScript/issues/63206) | Medium |
| vercel/next.js | [ESLint rule doesn't work with pageExtensions](https://github.com/vercel/next.js/issues/53473) | Medium |
| biomejs/biome | [Port prefer-includes from typescript-eslint](https://github.com/biomejs/biome/issues/7654) | Medium |
| biomejs/biome | [Port no-inline-styles from html-eslint](https://github.com/biomejs/biome/issues/9062) | Medium |

## Terraform / AWS / DevOps

| Project | Issue | Difficulty |
|---|---|---|
| terraform-provider-aws | [Add EMR on EKS parameter_configuration](https://github.com/hashicorp/terraform-provider-aws/issues/46502) | Medium |
| terraform-provider-aws | [S3 tables replication version token error](https://github.com/hashicorp/terraform-provider-aws/issues/46675) | Medium |
| aws/aws-cdk | [Add C8a instance class](https://github.com/aws/aws-cdk/issues/36722) | Easy |
| aws/aws-cdk | [StateMachine timeout doesn't apply to .asl.json](https://github.com/aws/aws-cdk/issues/37150) | Medium |
| opentofu/opentofu | [Docs: plan -out should mention encryption](https://github.com/opentofu/opentofu/issues/3693) | Easy |
| opentofu/opentofu | [Legacy state reader incorrectly triggered](https://github.com/opentofu/opentofu/issues/3643) | Medium |

## AI / Agent Frameworks

| Project | Issue | Difficulty |
|---|---|---|
| microsoft/autogen | [Improve import error messages](https://github.com/microsoft/autogen/issues/4605) | Easy |
| microsoft/autogen | [Get current message thread from group chat](https://github.com/microsoft/autogen/issues/6085) | Medium |
| pydantic/pydantic-ai | [Add OpenAI token counting](https://github.com/pydantic/pydantic-ai/issues/3430) | Medium |
| langchain-ai/langgraph | [Remove importlib.metadata usage](https://github.com/langchain-ai/langgraph/issues/5040) | Easy |
| langchain-ai/langchain | [AzureChatOpenAI creates new httpx client each time](https://github.com/langchain-ai/langchain/issues/32489) | Medium |
| run-llama/llama_index | [Support streaming tool results](https://github.com/run-llama/llama_index/issues/20409) | Medium |

---

## Contribution Workflow

```bash
# 1. Fork the repo on GitHub (click Fork button)
# 2. Clone your fork
git clone https://github.com/dlupiak/<repo-name>.git
cd <repo-name>

# 3. Create a branch
git checkout -b fix/short-description

# 4. Make changes, commit
git add .
git commit -m "Fix: short description of the change"

# 5. Push to your fork
git push origin fix/short-description

# 6. Open a Pull Request on GitHub targeting the upstream repo
```

## Tips

- Read `CONTRIBUTING.md` before starting
- Comment on the issue first to claim it
- Keep PRs small and focused
- Each merged PR levels up the **Pull Shark** achievement
