# Lommeregner

Dette repo er et skelet til **Lommeregner-opgaven**.

## Formål
Du skal lave et simpelt program, der kan fungere som en lommeregner og udføre de fire regnearter:
- Addition (+)
- Subtraktion (-)
- Multiplikation (*)
- Division (/)

## Indhold
- `Program.cs` → indgang til programmet (Main)
- `Calculator.cs` → klasse med metoder til regnearter (du skal selv implementere logikken)
- `skeleton_calculator.csproj` → projektfil til Visual Studio

## Opgave
1. Implementér metoderne i `Calculator.cs` (`Add`, `Subtract`, `Multiply`, `Divide`).
2. Udvid `Program.cs` så brugeren kan:
   - Indtaste to tal
   - Vælge en operator (+, -, *, /)
   - Få vist resultatet i konsollen
3. Sørg for, at programmet ikke crasher ved fejl (fx division med 0).
4. Gør det muligt at køre programmet flere gange, indtil brugeren selv vælger at stoppe.
5. Aflever programmet på GitHub og lav en kort præsentation (max 5 min), hvor du demonstrerer:
   - Eksempler på alle fire regnearter
   - At programmet kan køre igen uden at lukke

Held og lykke!
