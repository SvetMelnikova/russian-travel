.lead__title {
  font-weight: 900;
  font-size: 96px;
  line-height: 100px;
  text-align: center;
  max-width: 720px;
  margin: 56px auto 32px auto;
  padding: 0 48px;
}

@media screen and (max-width: 768px) {
  .lead__title {
    font-size: 12.5vw;
    line-height: 1.1;
    padding: 0 24px;
  }
}

@media screen and (max-width: 425px) {
  .lead__title {
    margin: 0 auto 16px auto;
    padding: 0 16px;
    font-size: 40px;
    line-height: 44px;
    width: 288px;
    height: 88px;
  }
}

.lead__subtitle{
  margin: 16px 0 40px;
  padding: 0;
  max-width: 288px;
  font-size: 16px;
  line-height: 20px;
  font-weight: 400;
  text-align: center;
}


@media screen and (min-width: 768px){
  .lead__subtitle{
    margin: 32px 0 56px;
    max-width: 640px;
    font-size: 30px;
    line-height: 36px;
  }
}

@media screen and (min-width: 1280px){
  .lead__subtitle{
    margin: 32px 0 64px;
  }
}

.lead__caption {
  padding-left: 0;
  margin: 8px 0 0;
  font-size: 10px;
  line-height: 14px;
  font-weight: normal;
  font-style: normal;
  text-align: start;
  letter-spacing: 0.15em;
  text-transform: uppercase;
}

@media screen and (max-width: 768px) {
  .lead__caption {
    padding-left: 24px;
  }
}

@media screen and (max-width: 425px) {
  .lead__caption {
    padding-left: 16px;
  }
}

.cover {
  background-image: url(../../images/cover-trains.jpg);
  background-size: cover;
  background-position: center;
  margin: 92px auto;
  max-width: 1184px;
  min-height: 740px;
  display: flex;
  align-items: stretch;
}

@media screen and (max-width: 1024px) {
  .cover {
    max-width: 100%;
    min-height: 640px;
  }
}

@media screen and (max-width: 768px) {
  .cover {
    min-height: 480px;
  }
}

@media screen and (max-width: 425px) {
  .cover {
    margin: 66px auto 64px auto;
    min-height: 200px;
  }
}

  font-size: 72px;
  font-weight: 900;
  line-height: 76px;
  text-align: center;
  max-width: 560px;
  margin: 0 auto 32px auto;
  color: white;
}

@media screen and (max-width: 768px) {
  .cover__title {
    font-size: 9.3vw;
    line-height: 1.1;
  }
}

@media screen and (max-width: 425px) {
  .cover__title {
    max-width: 288px;
    font-size: 32px;
    line-height: 35px;
  }

.cover__subtitle {
  margin: 0 auto;
  font-size: 18px;
  font-weight: 400;
  line-height: 22px;
  text-align: center;
  max-width: 360px;
  color: white;
}

@media screen and (max-width: 425px) {
  .cover__subtitle {
    font-size: 14px;
    line-height: 16px;
  }
}

.cover__overlay {
  position: relative;
  width: 100%;
  display: flex;
  text-decoration: none;
  flex-direction: column;
  justify-content: center;
  z-index: 0;
}

.cover__overlay::before {
  position: absolute;
  content: '';
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  background: #2a2c2f;
  opacity: .3;
  transition: opacity .7s ease-in;
  z-index: -1;
}

.cover__overlay:hover::before {
  opacity: .8;
}

.intro {
  max-width: 984px;
  margin: 0 auto;

}

@media screen and (max-width: 1024px) {
  .intro {
    max-width: 928px;
    margin: 0 48px;
  }
}

@media screen and (max-width: 768px) {
  .intro {
    max-width: 720px;
    margin: 0 24px;
  }
}

@media screen and (max-width: 425px) {
  .intro {
    max-width: 288px;
    margin: 0 16px;
  }
}
