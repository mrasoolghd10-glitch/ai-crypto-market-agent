# AI Crypto Market Agent

An automated crypto market monitoring and signal evaluation system built with n8n, APIs, Telegram and structured workflow monitoring.

## Overview

This project is a modular AI-assisted automation system designed to monitor cryptocurrency markets, detect important market events, evaluate signal quality, track outcomes and automatically generate performance and system health reports.

The system was designed as multiple independent workflows rather than one large automation, making it easier to maintain, monitor and scale.

## Core Features

* Automated crypto market scanning
* Multi-timeframe market analysis
* Market event detection
* Signal scoring and filtering
* Telegram notifications
* Signal outcome tracking
* Automated performance reports
* Workflow health monitoring
* Watchlist management
* Error monitoring
* Scheduled workflow execution
* Google Sheets data storage

## Workflow Architecture

The system includes separate workflows for:

1. Market Event Scanner
2. Signal Processing
3. Signal Outcome Monitoring
4. Performance Reporting
5. Watchlist Refresh
6. Workflow Health Monitoring
7. Error Monitoring

## Technologies

* n8n
* REST APIs
* Telegram Bot API
* Google Sheets
* JavaScript
* Webhooks
* Crypto Market APIs
* AI-assisted automation logic

## Example Workflow

Market Data
↓
Market Scanner
↓
Event Detection
↓
Signal Evaluation
↓
Filtering & Scoring
↓
Telegram Notification
↓
Outcome Monitoring
↓
Performance Report

## Monitoring

The system includes dedicated monitoring workflows to detect workflow failures, stale data and unhealthy execution states.

## Reporting

Automated reports provide information about:

* Detected market events
* Eligible signals
* Signal performance
* Average returns
* Validation progress
* Workflow health

## Project Status

Completed working automation system with market scanning, signal evaluation, reporting and workflow monitoring.

## Security

API keys, Telegram tokens, credential IDs and other private configuration values are excluded from this public repository.

## Screenshots

Screenshots of the workflows, Telegram outputs and automated reports will be added to this repository.

## About This Project

This is an independent portfolio project demonstrating the design of modular AI automation systems using n8n, APIs, external services and automated monitoring.
