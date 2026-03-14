# Copilot Instructions for Soc Ops Project

## Mandatory Development Checklist
Before committing changes:
- [ ] Run `dotnet build` to ensure no compilation errors
- [ ] Run `dotnet run` and verify the app works in browser
- [ ] Check for linting issues (add linter if needed)
- [ ] Test key features manually (game start, bingo logic, etc.)

## Project Overview
Soc Ops: Social Bingo game with .NET 10 and Blazor WebAssembly for in-person mixers.

## Tech Stack
- .NET 10, Blazor WebAssembly
- Bootstrap CSS
- GitHub Pages deployment

## Key Files
- `SocOps/Program.cs`: Entry point
- `SocOps/Services/BingoGameService.cs`: Game logic
- `SocOps/Data/Questions.cs`: Quiz data
- `SocOps/Components/`: UI components

## Development Workflow
- Run: `cd SocOps && dotnet run`
- Build: `cd SocOps && dotnet build`

## Available Agents
- **pixel-jam**: UI design
- **quiz-master**: Quiz creation
- **tdd**: TDD cycle
- **Plan**: Multi-step plans
- **CVE Remediator**: Security fixes

## Guidelines
- Use Blazor patterns
- Keep components focused
- Follow C# conventions
- Ensure responsive design
