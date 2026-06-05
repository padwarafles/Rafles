# Rafles
# Personal Portfolio Website

Portfolio website built with:

- React + TypeScript
- Tailwind CSS
- Vite

## Features

- Responsive Design
- Smooth Scrolling Navigation
- Hero Section
- About Me
- Skills Showcase
- Projects Gallery
- Contact Section

## Installation

import { useTranslation } from "react-i18next";

export default function HeroSection() {
  const { t } = useTranslation();

  return (
    <section>
      <h1>{t("home.hero.title")}</h1>
      <p>{t("home.hero.subtitle")}</p>
      <button>{t("home.hero.cta")}</button>
    </section>
  );
}
