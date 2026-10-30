# Changelog

## 1.0.28

- Venmo: back off failed re-logins, load .env in the login script
- Replace the Venmo server with settlement pay links

## 1.0.27

- Silence "use client" bundling warnings in the server build
- Report real health in the admin panel, drop the old add-on options

## 1.0.26

- Create the data directory before saving settings

## 1.0.25

- Settle: live month-to-date figures from Monarch, month-end close, username sign-in (#4)

## 1.0.24

- Move server settings from the add-on Configuration to each server's page

## 1.0.23

- Publish an add-on changelog with each release

## 1.0.22

- Drop passphrase sign-in from the web app; Ryan uses a PIN

## 1.0.21

- Let Ryan sign in to the web app with a PIN

## 1.0.20

- Add Financial Advisor web app; move to pnpm workspace

## 1.0.19

- Bind MCP servers to loopback with allowedHosts

## 1.0.18

- Rename planner to Financial Advisor; add Mort persona, logo and icons

## 1.0.17

- Match admin UI to MCP Host and show stored secrets (#3)

## 1.0.16

- Update planner.html

## 1.0.15

- Maintenance release

## 1.0.14

- Add App settings link to admin page

## 1.0.13

- monarch: use categories query for /health upstream check (#2)

## 1.0.12

- Split /heartbeat (alive) from /health (usable) on gateway and all three servers (#1)

## 1.0.11

- Add venmo_username and venmo_password add-on options

## 1.0.10

- Let /planner accept the 4-digit access code as well as the passphrase

## 1.0.9

- Add admin UI as a Home Assistant sidebar panel (ingress)

## 1.0.8

- Publish the add-on on host port 8106 so MCP Host can keep 8101

## 1.0.7

- Release: rebase onto main before recording the version

## 1.0.6

- Replace submodules with in-repo copies of monarch (f8baca2) and venmo (14ef140)
- Release: publish add-on metadata to the public store repository

## 1.0.5

- Listen on 8101 (published by default); move internal server ports to 9101-9103
- Use 8103-8105 for the internal server ports

## 1.0.4

- Initial Financial Assistant add-on: gateway, monarch/venmo submodules, financial-advisor server
- Bump monarch submodule to f8baca2 (HA add-on packaging)
- Config name change
- Point repo URLs, workflows and README at financial-advisor naming
- Rename add-on repository to Financial Advisor
- Release: push the version commit with the built-in token
