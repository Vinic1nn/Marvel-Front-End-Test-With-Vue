<template>
  <div id="menu">
    <section id="blackwidowSection" v-show="selectedHero === 'widow'">
      <div id="h1">
        <h1>Black Widow</h1>
      </div>
      <div id="img">
        <img src="../assets/img/BLACK-WIDOW.png" alt="Black Widow" />
      </div>
      <div id="p">
        <p>
          Natasha Romanoff was trained from a young age to cultivate a very
          specific set of skills in a Russian facility called the Red Room.
          There she honed the skills that would turn her into a human warrior
          who continues to stand shoulder-to-shoulder with super soldiers,
          Asgardians and people in armored suits. However, she eventually
          eschewed her KGB masters, switched allegiances and began working for
          the good guys.
        </p>

        <p>
          Exhibiting no super human abilities, the Black Widow boasts ultimate
          human levels of strength, agility, and stamina. She is extensively
          trained to near perfection in a variety of fighting styles, such as
          karate, judo, kung fu, and wrestling, and with all manner of
          weapons—both traditional and high-tech—combined with her background in
          gymnastics, acrobatics, and ballet to always accomplish her mission.
        </p>

        <p>
          She can use a simple handgun just as well as a Chitauri battle staff
          or even Captain America's shield. Her signature weapons include dual
          batons, a pair of Glock 26s and the Black Widow’s Bite—bracelets that
          discharge electricity. Romanoff also displays great skill when it
          comes to hacking in computers and technological systems to dig for
          information or regaining control.
        </p>
      </div>
    </section>
    <section id="spiderSection" v-show="selectedHero === 'spider'">
      <div id="h1">
        <h1>Spider-Man</h1>
      </div>
      <div id="img">
        <img src="../assets/img/SPIDER-MAN.png" alt="Spider-Man" />
      </div>
      <div id="p">
        <p>
          A bite from a spider somehow granted teenager Peter Parker its
          arachnid abilities and instead of using them for personal gain, he
          decided to help others with them. An orphan living with his aunt, May
          Parker, the boy chose to wear a mask while fighting crime so as not to
          burden her with his actions.
        </p>
        <p>
          Calling himself Spider-Man and sporting a pair of web-shooting devices
          he’d constructed, Parker wound up in internet videos which attracted
          the attention of Tony Stark. The billionaire industrialist deduced
          Spider-Man’s secret identity and approached Parker at his and May’s
          home in Queens, New York with a request for aid from the hero in an
          upcoming confrontation with Captain America and a group of other rogue
          Avengers and associates. Parker was initially hesitant to even admit
          his secret career as Spider-Man, but the thrill of adventure and
          Stark’s talk of responsibility drew him in and he accepted the
          invitation, as well as a new, high-tech costume and web-shooters.
        </p>
      </div>
    </section>
    <section id="thorSection" v-show="selectedHero === 'thor'">
      <div id="h1">
        <h1>Thor</h1>
      </div>
      <div id="img">
        <img src="../assets/img/THOR.png" alt="Thor" />
      </div>
      <div id="p">
        <p>
          Born 1500 years ago to Odin and Frigga, the king and queen of fabled
          Asgard, Thor grew into a mighty warrior and protector of his home and
          people. Thought to be rash and even reckless by his father, Thor
          nevertheless looked forward to the day of his ascension to the throne.
          But, his adoptive brother Loki schemed in private to ensure that day
          never arrived. He manipulated Thor into attacking the Frost Giants,
          legendary adversaries of the Asgardians and Loki’s people, and
          Odin—hoping to teach his son humility—divested Thor of his magic
          hammer Mjolnir and banished him to Midgard, the realm also known as
          Earth.
        </p>
        <p>
          Alone and unable to return to Asgard, Thor met scientists Jane Foster
          and Erik Selvig in the midst of their investigation into strange
          activity near a small New Mexico town. While his brother struggled
          with the limitations of mortals on Earth, Loki worked to ensure his
          own seizure of the Asgardian throne and planned to allow the Frost
          Giant king—his real father—into Asgard to slay Odin in his sleep. Back
          on Earth, Thor sacrificed himself to save the town from destruction
          and in doing so, impressed Odin enough to restore him to full
          Asgardian power.
        </p>
      </div>
    </section>
    <section id="ironmanSection" v-show="selectedHero === 'ironman'">
      <div id="h1">
        <h1>Iron Man</h1>
      </div>
      <div id="img">
        <img src="../assets/img/IRON-MAN.png" alt="Iron Man" />
      </div>
      <div id="p">
        <p>
          Genius inventor Tony Stark continued his father Howard Stark’s
          weaponry business after his parents’ untimely deaths and flew it to
          even greater heights of innovation. While in Afghanistan to
          demonstrate a new missile for the U.S. military, Stark’s convoy came
          under fire by a terrorist group known as the Ten Rings and he was
          severely wounded. Taken prisoner by the group, Stark awoke in their
          headquarters to learn that shrapnel near his heart had nearly cost him
          his life, but swift action by scientist and fellow prisoner Ho
          Yinsen—who had inserted a powerful electromagnet in Stark’s
          chest—would prolong it temporarily.
        </p>
        <p>
          Stalling his captors after they demanded he build them a new weapon,
          Stark replaced the magnet with the RT, a miniature version of a device
          originally designed by his father, the Arc Reactor. Furthermore, he
          and Yinsen created a crude suit of armor which could provide them the
          means with which to escape. The suit worked as planned, though Yinsen
          sacrificed himself in order to allow Tony enough time to power it up
          to fight their terrorist captors.
        </p>
      </div>
    </section>
    <section id="hawkeyeSection" v-show="selectedHero === 'hawkeye'">
      <div id="h1">
        <h1>Hawkeye</h1>
      </div>
      <div id="img">
        <img src="../assets/img/HAWKEYE.png" alt="Hulk" />
      </div>
      <div id="p">
        <p>
          Very little is known about the S.H.I.E.L.D. agent known as Hawkeye or
          his origins. An accomplished combatant and weapons master, he was
          present for Thor’s arrival on Earth, and was impressed with the God of
          Thunder. He was also instrumental in bringing over Natasha Romanoff,
          AKA Black Widow, to the side of S.H.I.E.L.D, sparing her life and
          offering her a path to redemption.
        </p>
        <p>
          For his extraordinary abilities, he was recruited by Nick Fury to be
          part of the Avengers Initiative. Unfortunately, in his first mission
          with the Avengers, he initially worked against them, thanks his mind
          being controlled by Loki, the Asgardian God of Mischief. After being
          broken free, however, the horrified Clint did work alongside his
          fellow Super Heroes to bring down the trickster god.
        </p>
        <p>
          Since then, he has managed to put his talents to good use against the
          Chitauri, Ultron, HYDRA, and even his fellow Avengers when it seemed
          necessary.
        </p>
      </div>
    </section>
    <section id="hulkSection" v-show="selectedHero === 'hulk'">
      <div id="h1">
        <h1>Hulk</h1>
      </div>
      <div id="img">
        <img src="../assets/img/HULK.png" alt="Hulk" />
      </div>
      <div id="p">
        <p>
          Bioscience genius Dr. Bruce Banner focused his major studies on the
          effects of gamma radiation on humans, working alongside Dr. Betty Ross
          at a Virginia University lab. Dr. Ross’ father, General “Thunderbolt”
          Ross of the U.S. Army, channeled Banner’s work into a program to
          develop weapons for the military, unbeknownst to both doctors. When
          Banner decided to test what he learned on himself, he triggered a
          fantastic transformation in himself that resulted in an immense,
          hulking figure fueled by his own rage.
        </p>
        <p>
          Having destroyed his lab as the creature, and inadvertently harming
          Ross in the process, Banner slipped away to avoid capture and study by
          the Army and began a desperate quest for a cure to his bizarre
          affliction.
        </p>
      </div>
    </section>
    <section id="captainSection" v-show="selectedHero === 'captain'">
      <div id="h1">
        <h1>Captain America</h1>
      </div>
      <div id="img">
        <img src="../assets/img/CAPTAIN-AMERICA.png" alt="Captain America" />
      </div>
      <div id="p">
        <p>
          Envious of his friend Bucky Barnes’ military enlistment, and
          undeterred by his own multiple rejections by the U.S. Army, physical
          weakling Steve Rogers made one more attempt to join the march of men
          to fight for their country in the dark days of World War II. Rogers’
          valiant wish to fight bullies wherever they were grabbed the attention
          of scientist Dr. Abraham Erskine, and he handpicked the idealistic
          young man for the Army’s Super-Soldier program under his supervision.
        </p>
        <p>
          Though Rogers learned of Erskine’s disastrous previous attempts to
          realize a super-soldier, Germany’s so-called “Red Skull,” he braved
          the process and emerged from it a new man. With a powerful body and
          heightened speed and reflexes, Rogers faced his first challenge when
          forced to chase down Dr. Erskine’s assassin immediately following the
          experiment. In doing so, he also learned of the involvement of Hydra,
          the Nazi science division, in the doctor’s murder.
        </p>
        <p>
          The Army moved swiftly to create a colorful, star-spangled persona for
          Steve Rogers they called “Captain America,” and put him on a tour to
          sell war bonds. Chafing at what he felt was inaction, Rogers jumped at
          the chance to join the real fighting when he received news of the
          capture of his friend Barnes’ army division and rushed to rescue the
          soldiers. Upon the successful completion of the unplanned mission—and
          a brief meeting with the Red Skull himself—Rogers determined his path
          as a one-man fighting force.
        </p>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  props: ["selectedHero"],
};
</script>


<style>
section {
  display: grid;
  grid-template-columns: 1fr 1fr 1.25fr 0.75fr;
  grid-template-rows: 100px 1fr;
  gap: 0px 0px;
  grid-template-areas:
    "h1 h1 h1 h1"
    ". Img Text ."
    ". . . .";
    margin-bottom: 25px;
}
section div#p {
  font-size: 14px;
  font-family: "Roboto";
  grid-area: Text;
}
section div#h1 {
  text-align: center;
  font-size: 30px;
  grid-area: h1;
}
section div#img {
  display: grid;
  grid-area: Img;
}
section div img {
  object-fit: contain;
  height: 80%;
  width: 80%;
}
</style>