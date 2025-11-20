apps/                     # Each PR app lives here (AI-generated)

shared/                   # Global Cockpit-wide shared modules

core/                     # Cockpit-level lifecycle, registration, routing

pr-app-template

app/                          # App entry + layout

features/                     # Domain-driven features (strict)

components/                   # App-specific reusable UI components

hooks/                        # App-specific hooks

context/                      # App context providers

services/                     # API clients, adapters

utils/                        # Pure utilities

types/                        # TS types/interfaces

constants/                    # Constants + enums

styles/                       # Style modules or tailwind configs

config/                       # Runtime config loaders

router/                       # If the PR app has multiple screens

main.tsx                      # Entry (exported to Cockpit)

