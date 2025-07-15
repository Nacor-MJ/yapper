# Yapper

Yapper is a Blazor-based financial simulation web application. It allows users to model and visualize wealth growth over time using customizable financial models.

## Features
- Add and simulate multiple financial models
- Visualize wealth growth with interactive charts (Syncfusion Blazor Charts)
- Adjustable parameters: monthly income, starting capital, wealth cap
- Clear all models or add new ones dynamically

## Technologies Used
- .NET 9
- Blazor (Interactive Server)
- Syncfusion Blazor Charts

## Getting Started

### Prerequisites
- [.NET 9 SDK](https://dotnet.microsoft.com/download)
- [Node.js](https://nodejs.org/) (if using frontend build tools)

### Running the Application
1. Clone the repository:
   ```sh
   git clone <your-repo-url>
   cd yapper
   ```
2. Restore dependencies:
   ```sh
   dotnet restore
   ```
3. Build and run the application:
   ```sh
   dotnet run --project yapper/yapper.csproj
   ```
4. Open your browser and navigate to `https://localhost:5001/graph` to use the graphing feature.

## Project Structure
- `yapper/` - Main application source code
  - `Components/Pages/Graph.razor` - Main graphing page
  - `wwwroot/` - Static assets (CSS, JS, images)
- `.gitignore` - Git ignore rules
- `yapper.sln` - Solution file

## License
This project is for educational and personal use. See LICENSE for details.
