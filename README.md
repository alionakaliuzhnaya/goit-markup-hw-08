# goit-markup-hw-08

homework 8

.hero { width: 480px; margin-left: auto; margin-right: auto; padding-top: 118px; padding-bottom:
118px; background-repeat: no-repeat; background-position: center; background-size: cover;
background-color: var(--bg-color-dark); background-image: linear-gradient(to right, rgba(47, 48, 58,
0.4), rgba(47, 48, 58, 0.4)), url('../../images/mobile/bg-main.jpg'); }

@media screen and (min-device-ratio: 2), screen and (min-resolution: 192dpi), screen and
(min-resolution: 2dppx) { .hero { background-image: linear-gradient(to right, rgba(47, 48, 58, 0.4),
rgba(47, 48, 58, 0.4)), url(../../images/mobile/bg-main@2x.jpg); } }

@media screen and (min-width: 768px) { .hero { width: 768px; background-image: linear-gradient(to
right, rgba(47, 48, 58, 0.4), rgba(47, 48, 58, 0.4)), url('../../images/tablet/bg-main.jpg'); }

@media screen and (min-device-ratio: 2), screen and (min-resolution: 192dpi), screen and
(min-resolution: 2dppx) { .hero { background-image: linear-gradient(to right, rgba(47, 48, 58, 0.4),
rgba(47, 48, 58, 0.4)), url('../../images/tablet/bg-main@2x.jpg'); } } }

@media screen and (min-width: 1200px) { .hero { max-width: 1600px; padding-top: 200px;
padding-bottom: 200px; background-image: linear-gradient(to right, rgba(47, 48, 58, 0.4), rgba(47,
48, 58, 0.4)), url('../../images/deckstope/bg-main.jpg'); } @media screen and (min-device-ratio: 2),
screen and (min-resolution: 192dpi), screen and (min-resolution: 2dppx) { .hero { background-image:
url(../../images/deckstope/bg-main@2x.jpg); } } }

.hero\_\_title { color: var(--basic-color); font-weight: 900; font-size: 24px; max-width: 360px;
line-height: 1.36; text-align: center; letter-spacing: 0.06em; text-transform: uppercase;
margin-top: 0px; margin-bottom: 30px; }

@media screen and (min-width: 1200px) { hero\_\_title { font-size: 44px; max-width: 696px; } }
