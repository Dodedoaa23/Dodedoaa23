<!DOCTYPE html>
<html lang="english">
  <head>
    <title>soul</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta charset="utf-8" />
    <meta property="twitter:card" content="summary_large_image" />
    <style data-tag="reset-style-sheet">
      html {  line-height: 1.15;}body {  margin: 0;}* {  box-sizing: border-box;  border-width: 0;  border-style: solid;}p,li,ul,pre,div,h1,h2,h3,h4,h5,h6,figure,blockquote,figcaption {  margin: 0;  padding: 0;}button {  background-color: transparent;}button,input,optgroup,select,textarea {  font-family: inherit;  font-size: 100%;  line-height: 1.15;  margin: 0;}button,select {  text-transform: none;}button,[type="button"],[type="reset"],[type="submit"] {  -webkit-appearance: button;}button::-moz-focus-inner,[type="button"]::-moz-focus-inner,[type="reset"]::-moz-focus-inner,[type="submit"]::-moz-focus-inner {  border-style: none;  padding: 0;}button:-moz-focus,[type="button"]:-moz-focus,[type="reset"]:-moz-focus,[type="submit"]:-moz-focus {  outline: 1px dotted ButtonText;}a {  color: inherit;  text-decoration: inherit;}input {  padding: 2px 4px;}img {  display: block;}html { scroll-behavior: smooth  }
    </style>
    <style data-tag="default-style-sheet">
      html {
        font-family: Inter;
        font-size: 16px;
      }
      body {
        :root {
  --dl-size-size-large: 144px;
  --dl-size-size-small: 48px;
  --dl-size-size-medium: 96px;
  --dl-size-size-xlarge: 192px;
  --dl-size-size-xsmall: 16px;
  --dl-space-space-unit: 16px;
  --dl-size-size-xxlarge: 288px;
  --dl-size-size-maxwidth: 1400px;
  --dl-color-theme-accent1: #FFFFFF;
  --dl-color-theme-accent2: #F5D1B0;
  --dl-radius-radius-round: 50%;
  --dl-color-theme-primary1: #BF4408;
  --dl-color-theme-primary2: #E65103;
  --dl-space-space-halfunit: 8px;
  --dl-space-space-sixunits: 96px;
  --dl-space-space-twounits: 32px;
  --dl-radius-radius-radius2: 2px;
  --dl-radius-radius-radius4: 4px;
  --dl-radius-radius-radius8: 8px;
  --dl-space-space-fiveunits: 80px;
  --dl-space-space-fourunits: 64px;
  --dl-color-theme-secondary1: #FFFFFF;
  --dl-color-theme-secondary2: #FBF1EB;
  --dl-space-space-threeunits: 48px;
  --dl-color-theme-neutral-dark: #191818;
  --dl-radius-radius-cardradius: 8px;
  --dl-color-theme-neutral-light: #FBFAF9;
  --dl-radius-radius-imageradius: 8px;
  --dl-radius-radius-inputradius: 24px;
  --dl-radius-radius-buttonradius: 24px;
  --dl-space-space-oneandhalfunits: 24px;
}
.button {
  color: var(--dl-color-theme-neutral-dark);
  display: inline-block;
  padding: 0.5rem 1rem;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  border-radius: 4px;
  background-color: var(--dl-color-theme-neutral-light);
}
.input {
  color: var(--dl-color-theme-neutral-dark);
  cursor: auto;
  padding: 0.5rem 1rem;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  border-radius: 4px;
  background-color: var(--dl-color-theme-neutral-light);
}
.textarea {
  color: var(--dl-color-theme-neutral-dark);
  cursor: auto;
  padding: 0.5rem;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  border-radius: 4px;
  background-color: var(--dl-color-theme-neutral-light);
}
.list {
  width: 100%;
  margin: 1em 0px 1em 0px;
  display: block;
  padding: 0px 0px 0px 1.5rem;
  list-style-type: none;
  list-style-position: outside;
}
.list-item {
  display: list-item;
}
.teleport-show {
  display: flex !important;
  transform: none !important;
}
.thq-input {
  color: var(--dl-color-theme-neutral-dark);
  cursor: auto;
  outline: none;
  padding: 0.5rem 1rem;
  align-self: stretch;
  text-align: center;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  border-radius: var(--dl-radius-radius-inputradius);
  background-color: var(--dl-color-theme-neutral-light);
}
.thq-input:focus {
  outline: 1px solid var(--dl-color-theme-primary1);
}
.thq-button-filled {
  gap: var(--dl-space-space-halfunit);
  fill: var(--dl-color-theme-secondary1);
  color: var(--dl-color-theme-secondary1);
  cursor: pointer;
  display: flex;
  transition: 0.3s;
  align-items: center;
  font-weight: bold;
  padding-top: var(--dl-space-space-halfunit);
  white-space: nowrap;
  border-color: var(--dl-color-theme-primary1);
  border-width: 1px;
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: var(--dl-radius-radius-buttonradius);
  padding-right: var(--dl-space-space-oneandhalfunits);
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
  background-color: var(--dl-color-theme-primary1);
}
.thq-button-filled:hover {
  fill: var(--dl-color-theme-secondary2);
  color: var(--dl-color-theme-secondary2);
  border-color: var(--dl-color-theme-primary2);
  background-color: var(--dl-color-theme-primary2);
}
.thq-button-outline {
  gap: var(--dl-space-space-halfunit);
  fill: var(--dl-color-theme-primary1);
  color: var(--dl-color-theme-primary1);
  border: 1px solid;
  cursor: pointer;
  display: flex;
  transition: 0.3s;
  align-items: center;
  font-weight: bold;
  padding-top: var(--dl-space-space-halfunit);
  white-space: nowrap;
  border-color: var(--dl-color-theme-primary1);
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: var(--dl-radius-radius-buttonradius);
  padding-right: var(--dl-space-space-oneandhalfunits);
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
}
.thq-button-outline:hover {
  fill: var(--dl-color-theme-secondary2);
  color: var(--dl-color-theme-secondary2);
  border-color: var(--dl-color-theme-primary2);
  background-color: var(--dl-color-theme-primary2);
}
.thq-button-flat {
  gap: var(--dl-space-space-halfunit);
  fill: var(--dl-color-theme-primary1);
  color: var(--dl-color-theme-primary1);
  cursor: pointer;
  display: flex;
  transition: 0.3s;
  align-items: center;
  font-weight: bold;
  padding-top: var(--dl-space-space-halfunit);
  white-space: nowrap;
  border-color: transparent;
  border-width: 1px;
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: var(--dl-radius-radius-buttonradius);
  padding-right: var(--dl-space-space-oneandhalfunits);
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
}
.thq-button-flat:hover {
  fill: var(--dl-color-theme-secondary1);
  color: var(--dl-color-theme-secondary1);
  border-color: var(--dl-color-theme-primary2);
  background-color: var(--dl-color-theme-primary2);
}
.thq-heading-1 {
  font-size: 48px;
  font-family: STIX Two Text;
  font-weight: 700;
  line-height: 1.5;
}
.thq-heading-2 {
  font-size: 35px;
  font-family: STIX Two Text;
  font-weight: 600;
  line-height: 1.5;
}
.thq-heading-3 {
  font-size: 26px;
  font-family: STIX Two Text;
  font-weight: 600;
  line-height: 1.5;
}
.thq-body-large {
  font-size: 18px;
  font-family: Noto Sans;
  line-height: 1.5;
}
.thq-body-small {
  font-size: 16px;
  font-family: Noto Sans;
  line-height: 1.5;
}
.thq-team-image-round {
  width: 80px;
  height: 80px;
  object-fit: cover;
  border-radius: 50%;
}
.thq-section-padding {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-fiveunits);
  position: relative;
  align-items: center;
  flex-direction: column;
}
.thq-section-max-width {
  width: 100%;
  max-width: var(--dl-size-size-maxwidth);
}
.thq-img-ratio-1-1 {
  width: 100%;
  object-fit: cover;
  aspect-ratio: 1/1;
  border-radius: var(--dl-radius-radius-imageradius);
}
.thq-img-ratio-16-9 {
  width: 100%;
  object-fit: cover;
  aspect-ratio: 16/9;
  border-radius: var(--dl-radius-radius-imageradius);
}
.thq-img-ratio-4-3 {
  width: 100%;
  object-fit: cover;
  aspect-ratio: 4/3;
  border-radius: var(--dl-radius-radius-imageradius);
}
.thq-img-ratio-4-6 {
  width: 100%;
  object-fit: cover;
  aspect-ratio: 4/6;
  border-radius: var(--dl-radius-radius-imageradius);
}
.thq-img-round {
  width: 100%;
  border-radius: var(--dl-radius-radius-round);
}
.thq-flex-column {
  gap: var(--dl-space-space-twounits);
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.thq-flex-row {
  gap: var(--dl-space-space-twounits);
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
}
.thq-grid-6 {
  display: grid;
  grid-gap: var(--dl-space-space-twounits);
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
}
.thq-grid-5 {
  display: grid;
  grid-gap: var(--dl-space-space-twounits);
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
}
.thq-card {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding: var(--dl-space-space-twounits);
  align-items: stretch;
  border-radius: var(--dl-radius-radius-cardradius);
  flex-direction: column;
}
.thq-box-shadow {
  box-shadow: 0px 0px 5px -2px var(--dl-color-theme-neutral-dark);
}
.thq-grid-3 {
  display: grid;
  grid-gap: var(--dl-space-space-twounits);
  grid-template-columns: 1fr 1fr 1fr;
}
.thq-grid-4 {
  display: grid;
  grid-gap: var(--dl-space-space-twounits);
  grid-template-columns: 1fr 1fr 1fr 1fr;
}
.thq-grid-2 {
  width: 100%;
  display: grid;
  grid-gap: var(--dl-space-space-twounits);
  grid-template-columns: 1fr 1fr;
}
.thq-checkbox {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.thq-select {
  cursor: pointer;
  appearance: none;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-inputradius);
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-halfunit);
  background-color: var(--dl-color-theme-neutral-light);
  background-image: url('data:image/svg+xml;charset=US-ASCII,%3Csvg width%3D%2220%22 height%3D%2220%22 xmlns%3D%22http%3A//www.w3.org/2000/svg%22 viewBox%3D%220 0 20 20%22 fill%3D%22%23000%22%3E%3Cpath d%3D%22M4.293 7.293a1 1 0 011.414 0L10 11.586l4.293-4.293a1 1 0 111.414 1.414l-5 5a1 1 0 01-1.414 0l-5-5a1 1 0 010-1.414z%22/%3E%3C/svg%3E');
  background-repeat: no-repeat;
  background-position: right 8px center;
}
.thq-divider-horizontal {
  width: 100%;
  height: 1px;
  background-color: var(--dl-color-theme-neutral-dark);
}
.thq-icon-small {
  width: 24px;
  height: 24px;
}
.thq-button-icon {
  fill: var(--dl-color-theme-secondary1);
  padding: 3px;
  transition: 0.3s;
  border-radius: var(--dl-radius-radius-round);
}
.thq-button-icon:hover {
  fill: var(--dl-color-theme-secondary2);
}
.thq-icon-medium {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
}
.thq-icon-x-small {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.thq-link {
  cursor: pointer;
  display: inline-block;
  overflow: hidden;
  background: linear-gradient(to right, var(--dl-color-theme-primary1) 50%, var(--dl-color-theme-neutral-dark) 50%);
  transition: background-position 300ms ease;
  font-weight: 600;
  background-clip: text;
  background-size: 200% 100%;
  background-position: 100%;
  -webkit-text-fill-color: transparent;
}
.thq-link:hover {
  background-position: 0 100%;
}
.thq-grid-auto-300 {
  display: grid;
  grid-gap: var(--dl-space-space-oneandhalfunits);
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}
.thq-animated-group-vertical-reverse {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  animation: scroll-y 20s linear infinite;
  align-items: flex-start;
  flex-direction: column;
  justify-content: space-around;
  animation-direction: reverse;
}
.thq-animated-group-horizontal-reverse {
  gap: var(--dl-space-space-unit);
  display: flex;
  animation: scroll-x 20s linear infinite;
  min-width: 100%;
  align-items: center;
  flex-shrink: 0;
  justify-content: space-around;
  animation-direction: reverse;
}
.thq-animated-group-vertical {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  animation: scroll-y 20s linear infinite;
  align-items: flex-start;
  flex-direction: column;
  justify-content: space-around;
}
.thq-animated-group-horizontal {
  gap: var(--dl-space-space-unit);
  display: flex;
  animation: scroll-x 20s linear infinite;
  min-width: 100%;
  align-items: center;
  flex-shrink: 0;
  justify-content: space-around;
}
.thq-animated-group-container-vertical {
  gap: var(--dl-space-space-unit);
  display: flex;
  overflow: hidden;
  flex-direction: column;
}
.thq-animated-group-container-horizontal {
  gap: var(--dl-space-space-unit);
  display: flex;
  overflow: hidden;
}
.thq-mask-image-vertical {
  mask-image: linear-gradient(to bottom, transparent, black 1%, black 99%, transparent);
}
.thq-mask-image-horizontal {
  mask-image: linear-gradient(to right, transparent, black 1%, black 99%, transparent);
}
.thq-img-scale {
  transition: 0.3s;
}
.thq-img-scale:hover {
  scale: 1.05;
}
.thq-animated-card-bg-1 {
  width: 100%;
  height: 100%;
  transition: transform 0.3s;
  border-radius: var(--dl-radius-radius-cardradius);
  background-color: var(--dl-color-theme-accent1);
}
.thq-animated-card-bg-2 {
  transition: transform 0.3s;
  border-radius: var(--dl-radius-radius-cardradius);
  background-color: var(--dl-color-theme-accent2);
}
.thq-button-animated {
  outline: none;
  z-index: 1;
  overflow: hidden;
  position: relative;
  border-width: 2px;
}
.thq-input::placeholder {
  text-align: center;
  vertical-align: middle;
}
.thq-animated-group-container-vertical:hover div {
  animation-play-state: paused;
}
.thq-animated-group-container-horizontal:hover div {
  animation-play-state: paused;
}
.thq-animated-card-bg-2:has([data-animated="true"]:hover) {
  transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1) rotateX(0deg) rotateY(0deg) rotateZ(3deg) skew(0deg, 0deg);
}
.thq-animated-card-bg-1:has([data-animated="true"]:hover) {
  transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1) rotateX(0deg) rotateY(0deg) rotateZ(-6deg) skew(0deg, 0deg);
}
.thq-button-animated:before {
  top: 0;
  left: -20%;
  color: var(--dl-color-theme-neutral-light);
  width: 200%;
  height: 101%;
  content: "";
  z-index: 1;
  position: absolute;
  transform: scaleX(0);
  transition: transform 0.5s;
  border-radius: var(--dl-radius-radius-buttonradius);
  background-color: var(--dl-color-theme-neutral-dark);
  transform-origin: 0 0;
  transition-timing-function: cubic-bezier(0.5, 1.6, 0.4, 0.7);
}
.thq-button-animated:hover::before {
  color: var(--dl-color-theme-neutral-light);
  z-index: -1;
  transform: scaleX(1);
}
.BodySmallStrong {
  font-size: 14px;
  font-style: normal;
  font-family: Inter;
  font-weight: 700px;
  font-stretch: normal;
  letter-spacing: 0em;
}
.Content {
  font-size: 16px;
  font-family: Inter;
  font-weight: 400;
  line-height: 1.15;
  text-transform: none;
  text-decoration: none;
}
.SingleLineBodyBase {
  font-size: 16px;
  font-style: normal;
  font-family: Inter;
  font-weight: 400px;
  font-stretch: normal;
  letter-spacing: 0em;
}
@media(max-width: 991px) {
  .thq-grid-4 {
    grid-template-columns: 1fr 1fr 1fr;
  }
}
@media(max-width: 767px) {
  .thq-section-padding {
    padding: var(--dl-space-space-threeunits);
  }
  .thq-flex-column {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .thq-flex-row {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .thq-grid-6 {
    grid-gap: var(--dl-space-space-oneandhalfunits);
    grid-template-columns: 1fr 1fr 1fr;
  }
  .thq-grid-5 {
    grid-gap: var(--dl-space-space-oneandhalfunits);
    grid-template-columns: 1fr 1fr 1fr;
  }
  .thq-card {
    padding: var(--dl-space-space-oneandhalfunits);
  }
  .thq-grid-3 {
    grid-gap: var(--dl-space-space-oneandhalfunits);
    grid-template-columns: 1fr 1fr;
  }
  .thq-grid-4 {
    grid-gap: var(--dl-space-space-oneandhalfunits);
    flex-direction: row;
    grid-template-columns: 1fr 1fr;
  }
  .thq-grid-2 {
    grid-gap: var(--dl-space-space-oneandhalfunits);
    grid-template-columns: 1fr;
  }
  .thq-img-scale {
    width: 100%;
  }
}
@media(max-width: 479px) {
  .thq-section-padding {
    padding: var(--dl-space-space-oneandhalfunits);
  }
  .thq-flex-column {
    gap: var(--dl-space-space-unit);
  }
  .thq-flex-row {
    gap: var(--dl-space-space-unit);
  }
  .thq-grid-6 {
    grid-gap: var(--dl-space-space-unit);
    grid-template-columns: 1fr 1fr;
  }
  .thq-grid-5 {
    grid-gap: var(--dl-space-space-unit);
    grid-template-columns: 1fr 1fr;
  }
  .thq-grid-3 {
    grid-gap: var(--dl-space-space-unit);
    align-items: center;
    grid-template-columns: 1fr;
  }
  .thq-grid-4 {
    grid-gap: var(--dl-space-space-unit);
    align-items: center;
    flex-direction: column;
    grid-template-columns: 1fr;
  }
  .thq-grid-2 {
    grid-gap: var(--dl-space-space-unit);
  }
  .thq-grid-auto-300 {
    grid-template-columns: 1fr;
  }
}
        font-weight: 400;
        font-style:normal;
        text-decoration: none;
        text-transform: none;
        letter-spacing: normal;
        line-height: 1.15;
        color: var(--dl-color-theme-neutral-dark);
        background: var(--dl-color-theme-neutral-light);
        fill: var(--dl-color-theme-neutral-dark);
      }
    </style>
    <link
      rel="stylesheet"
      href="https://unpkg.com/animate.css@4.1.1/animate.css"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Metrophobic:wght@400&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=ABeeZee:ital,wght@0,400;1,400&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Itim:wght@400&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=ABeeZee:ital,wght@0,400;1,400&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=ABeeZee:ital,wght@0,400;1,400&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Aguafina+Script:wght@400&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=ABeeZee:ital,wght@0,400;1,400&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=STIX+Two+Text:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500;1,600;1,700&amp;display=swap"
      data-tag="font"
    />
    <link
      rel="stylesheet"
      href="https://unpkg.com/@teleporthq/teleport-custom-scripts/dist/style.css"
    />
  </head>
  <body>
    <link rel="stylesheet" href="./style.css" />
    <div>
      <link href="./404.css" rel="stylesheet" />
      <div class="not-found-container1">
        <h3>OOPS! PAGE NOT FOUND</h3>
        <div class="not-found-container2">
          <h1 class="not-found-text2">404</h1>
        </div>
        <div class="not-found-container3">
          <h2 class="not-found-text3">
            WE ARE SORRY, BUT THE PAGE YOU REQUESTED WAS NOT FOUND
          </h2>
        </div>
      </div>
    </div>
  </body>
</html>

