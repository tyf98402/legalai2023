<template>
  <div style="width: 70%;margin-left: 15%;margin-bottom: 80px">
    <article class="prose prose-lg max-w-none align-middle tracking-normal">
      <br>
      <h1 class="font-semibold">
        <span class="text-8xl font-black">The 2nd</span>
        <span class="text-5xl font-black">International <span class="text-6xl font-black">Workshop</span> on Legal Intelligence Held in conjunction with ICDM 2023（LegalAI@ICDM2023）</span>
      </h1>
      <br>
      <div>
        <span class="badge badge-accent">News:</span>
        <span class="indent-8" style="font-size: 15px">{{news}}</span>
<!--        <a class="link link-primary font-italic" style="font-size: 15px">video</a>-->
      </div>
      <br>
      <h2 class="text-3xl font-black">Welcome to Legal AI!</h2>
      <p class="indent-8">{{proposal}}</p>
      <br>
      <div class="w-100 carousel rounded-box" style="width: 70%;height: 70%;">
        <div class="carousel-item w-full">
          <img src="../assets/images/figure-new.jpg" class="w-full">
        </div>
      </div>
      <br>
      <h2 class="text-3xl font-black">WORKSHOP PROGRAM</h2>
      <a class="link link-secondary font-italic">TOD</a>
      <br>
<!--      <div>-->
<!--        <ul style="list-style-type:disc;padding-left: 20px">-->
<!--          <li>8:30 - 8:45AM &#45;&#45; Opening & Welcome</li>-->
<!--          <li>8:45 - 9:30AM &#45;&#45; Keynote 1: Legal Intelligence Research in Industry-->
<!--            <ul class="circle">-->
<!--              <li>-->
<!--                <div class="badge badge-secondary">Yating Zhang</div>-->
<!--                <div class="badge badge-secondary little-margin-left">Changlong Sun</div>-->
<!--              </li>-->
<!--            </ul>-->
<!--          </li>-->
<!--          <li>9:30 - 10:15AM &#45;&#45; Keynote 2: On the Importance of Domain Knowledge for Computational Law-->
<!--            <ul class="circle">-->
<!--              <li><div class="badge badge-secondary">Douglas W. Oard</div>-->
<!--                <ul class="square">-->
<!--                  <li><div class="badge">Bio:</div> Douglas W. Oard is a Professor at the University of Maryland, College Park (USA), with joint appointments in the College of Information Studies (Maryland’s iSchool) and the University of Maryland Institute for Advanced Computer Studies (UMIACS). His research interests center around the use of emerging technologies to support information seeking. Additional information is available at <a class="link link-primary font-italic" href="http://terpconnect.umd.edu/~oard/">http://terpconnect.umd.edu/~oard/</a>.</li>-->
<!--                </ul>-->
<!--              </li>-->
<!--            </ul>-->
<!--          </li>-->
<!--          <li>Accepted Paper Presentation</li>-->
<!--          <li>10:15-11:00AM (each paper has 12min for presentation and 3 min for QA )-->
<!--            <ul class="circle">-->
<!--              <li><div class="badge badge-accent">Paper Talk 1:</div> Automatic Text Revision with Application to Legal Documents-->
<!--                <ul class="square">-->
<!--                  <li>-->
<!--                    <div class="badge badge-secondary">Yiquan Wu</div>-->
<!--                    <div class="badge badge-secondary little-margin-left">Kun Kuang</div>-->
<!--                    <div class="badge badge-secondary little-margin-left">Fei Wu</div>-->
<!--                    <div class="badge badge-secondary little-margin-left">Zhejiang University</div>-->
<!--                  </li>-->
<!--                </ul>-->
<!--              </li>-->
<!--              <li><div class="badge badge-accent">Paper Talk 2:</div> AI-lead Court Debate Case Investigation-->
<!--                <ul class="square">-->
<!--                  <li>-->
<!--                    <div class="badge badge-secondary">Changzhen Ji</div>-->
<!--                    <div class="badge badge-secondary little-margin-left">Conghui Zhu</div>-->
<!--                    <div class="badge badge-secondary little-margin-left">Tiejun Zhao</div>-->
<!--                    <div class="badge badge-secondary little-margin-left">Harbin Institute of Technology</div>-->
<!--                  </li>-->
<!--                </ul>-->
<!--              </li>-->
<!--              <li><div class="badge badge-accent">Paper Talk 3:</div> Judgment Prediction Based on Case Life Cycle-->
<!--                <ul class="square"><li>-->
<!--                  <div class="badge badge-secondary">Luyao Ma</div>-->
<!--                  <div class="badge badge-secondary little-margin-left">Wei Ye</div>-->
<!--                  <div class="badge badge-secondary little-margin-left">Peking University</div>-->
<!--                </li></ul>-->
<!--              </li>-->
<!--            </ul>-->
<!--          </li>-->
<!--          <li>Break for 10 min</li>-->
<!--          <li>Previous paper sharing</li>-->
<!--          <li>11:10 - 12:00AM : (each paper has 12 min)-->
<!--            <ul class="circle">-->
<!--              <li><div class="badge badge-accent">Paper Talk 4:</div> Legal Artificial Intelligence : Have You Lost a Piece from Jigsaw Puzzle?-->
<!--                <ul class="square"><li><div class="badge badge-secondary">Xiaozhong Liu</div></li></ul>-->
<!--              </li>-->
<!--            </ul>-->
<!--            <ul class="circle">-->
<!--              <li><div class="badge badge-accent">Paper Talk 5:</div> Legal Summarization for Multi-role Debate Dialogue via Controversy Focus Mining and Multi-task Learning-->
<!--                <ul class="square"><li><div class="badge badge-secondary">Xinyu Duan</div></li></ul>-->
<!--              </li>-->
<!--            </ul>-->
<!--            <ul class="circle">-->
<!--              <li><div class="badge badge-accent">Paper Talk 6:</div> Masking Orchestration: Multi-task Pretraining for Multi-role Dialogue Representation Learning-->
<!--                <ul class="square"><li><div class="badge badge-secondary">Tianyi Wang</div></li></ul>-->
<!--              </li>-->
<!--            </ul>-->
<!--            <ul class="circle">-->
<!--              <li><div class="badge badge-accent">Paper Talk 7:</div> Legal Intelligence for E-commerce: Multi-task Learning by Leveraging Multiview Dispute Representation-->
<!--                <ul class="square"><li><div class="badge badge-secondary">Xin Zhou</div></li></ul>-->
<!--              </li>-->
<!--            </ul>-->
<!--          </li>-->
<!--        </ul>-->
<!--      </div>-->
      <br>
      <h2 class="text-3xl font-black">CALL FOR PAPERS</h2>
      <p class="indent-8">
        The workshop will include original contributions on theo- ries, methodologies, and applications of legal text/data mining, legal document retrieval, machine learning, legal knowledge graph generation/mining, natural language processing, legal knowledge representation in the legal ecosystem and explain- able AI in Law. The scope of the workshop includes, but is not limited to, the following areas:
      </p>
      <ul style="list-style-type:disc;padding-left: 20px">
        <li>Legal-specific Pretraining Language Model</li>
        <li>Legal Text Mining</li>
        <li>Legal knowledge graph creation and application</li>
        <li>Legal dialog and legal QA system</li>
        <li>Legal document, e.g., verdict, generation</li>
        <li>Court debate mining</li>
        <li>Penalty prediction</li>
        <li>Legal machine reading comprehension</li>
        <li>Legal (open) dataset generation</li>
        <li> Evaluation for legal tasks</li>
        <li>Societal and ethical challenges of legal intelligence • Legal data privacy protection</li>
        <li>Legal AI application and system</li>
        <li>Explainability & fairness of ML models in law</li>
        <li>Computational social justice</li>
        <li>Human factor for legal AI</li>
      </ul>
      <p class="indent-8">We especially encourage workshop participates use the open
        legal datasets, e.g., Artificial Intelligence for Legal Assistance (AILA 2019) and CAIL 2019, and they can also create and share the publicly available dataset to motivate other scholars to further investigate this important domain.</p>
      <br>
      <h2 class="text-3xl font-black">SUBMISSIONS</h2>
      <p class="indent-8">We welcome original research papers that present novel research ideas and we encourage submissions of greenhouse work, which present early stages of cutting-edge research and development. Position papers regarding work on the beginning, demo, and industry papers are also welcome.</p>
      <p class="indent-8">All papers must be original and not simultaneously submitted to another journal or conference. The following paper categories are welcome:</p>
      <ul style="list-style-type:disc;padding-left: 20px">
        <li>Novel research papers in full (up to 8 pages) or short length (up to 4 pages)</li>
        <li>Work-in-progress papers (up to 4 pages)</li>
        <li>Demo papers (up to 2 pages)</li>
      </ul>
      <!-- ACM "sigconf" template format -->
<!--      <p class="indent-8"> All submissions should be formatted according to the official <a class="link link-primary font-italic">ACM "sigconf" template format</a>.Papers must be submitted before deadline via EasyChair at this <a class="link link-primary font-italic">Link</a>.</p>-->
      <br>
      <h2 class="text-3xl font-black">IMPORTANT DATES</h2>
      <ul style="list-style-type:disc;padding-left: 20px">
<!--        <li>March 5, 2023: Workshop proposals deadline</li>-->
<!--        <li>April 9, 2023: Workshop proposals notification</li>-->
        <li>September 3, 2023: Workshop papers submission</li>
        <li>September 24, 2023: Notification of workshop papers acceptance to authors</li>
        <li>October 1, 2023: Camera-ready deadline and copyright form</li>
        <li>December 4, 2023: Workshops date</li>
      </ul>
      <br>
      <h2 class="text-3xl font-black">ORGANIZERS</h2>
      <div class="card card-side bg-base-100 shadow-x2">
        <figure class="px-4 pt-4">
          <img src="../assets/images/yating.png" class="rounded-xl" width="100" height="200">
        </figure>
        <div class="card-body item-center text-center">
          <h2 class="card-title">Yating Zhang</h2>
<!--          <p style="font-size: 15px;text-align: left" class="indent-8">-->
<!--            Is the advanced NLP Algorithm scientist from Alibaba DAMO Academy. She got her Ph.D at Kyoto University in Japan. Her research interests lie at the intersection of Machine Learning and Information Retrieval/Natural Language Processing, in particular on areas relating to legal information retrieval, legal knowledge construction and legal document summarization etc. She serves as the co-leader of Legal Intelligence Commercialization project, which has been adopted in Zhejiang Higher People’s court and its subordinate courts as well as a number of legal companies. She also serves as the co-PI of the National Legal AI Court project.-->
<!--          </p>-->
          <div class="card-actions">
            <div class="badge">Alibaba Group</div>
            <div class="badge little-margin-left">China</div>
          </div>
        </div>
      </div>
      <div class="card card-side bg-base-100 shadow-x2">
        <figure class="px-4 pt-4">
          <img src="../assets/images/Xiaozhong_Liu.jpg" class="rounded-xl" width="100" height="300">
        </figure>
        <div class="card-body item-center text-center">
          <h2 class="card-title"> Xiaozhong Liu</h2>
<!--          <p style="font-size: 15px;text-align: left" class="indent-8">-->
<!--            Is the Associate Professor at Computer Science and Data Science, WPI. Before that, he was Associate Professor at School of Informatics, Computing and Engineering Indiana University Bloomington. His research interests include natural language processing (NLP), text/graph mining, information retrieval/recommendation, metadata, and computational social science. His research is focusing on NLP, Information Retrieval, Text Mining and Knowledge Graph Mining. He leads the champion team to win the CAIL 2018 Legal Prediction Competition, and he serves as the PI of Legal NLP and Heterogeneous Legal Graph Mining project at Indiana University.-->
<!--          </p>-->
          <div class="card-actions">
            <di class="badge">Worcester Polytechnic Institute</di>
<!--            <div class="badge little-margin-left">WPI</div>-->
            <div class="badge little-margin-left">USA</div>
          </div>
        </div>
      </div>
      <div class="card card-side bg-base-100 shadow-x2">
        <figure class="px-4 pt-4">
          <img src="../assets/images/changlong.png" class="rounded-xl" width="100" height="200">
        </figure>
        <div class="card-body item-center text-center">
          <h2 class="card-title">Changlong Sun</h2>
          <!--          <p style="font-size: 15px;text-align: left" class="indent-8">-->
          <!--            Is the senior NLP algorithm scientist from Alibaba DAMO Academy. While he is leading the sentiment analysis and anti-spam research teams, he also serves as the leader of Legal Intelligence Commercialization project, which is a twenty-million dollar investment to explore innovative AI solutions for legal ecosystem. He has published more than 10 papers in the top NLP and data mining conferences along with more than 50 patents in data mining and machine/deep learning.-->
          <!--          </p>-->
          <div class="card-actions">
            <div class="badge">Alibaba Group</div>
            <div class="badge little-margin-left">China</div>
          </div>
        </div>
      </div>
      <div class="card card-side bg-base-100 shadow-x2">
        <figure class="px-4 pt-4">
          <img src="../assets/images/feiwu.png" class="rounded-xl" width="100" height="200">
        </figure>
        <div class="card-body item-center text-center">
          <h2 class="card-title">Fei Wu</h2>
<!--          <p style="font-size: 15px;text-align: left" class="indent-8">-->
<!--            Received his B.Sc., M.Sc. and Ph.D. degrees in computer science from Lanzhou University, University of Macau and Zhejiang University in 1996, 1999 and 2002 respectively. From October, 2009 to August 2010, Fei Wu was a visiting scholar at Prof. Bin Yu’s group, University of California, Berkeley. Currently, He is a Qiushi distinguished professor of Zhejiang University at the college of computer science. He is the vice-dean of college of computer science, and the director of Institute of Artificial Intelligence of Zhejiang University. He is the chairman of IEEE CAS Hangzhou-Chapter since Oct, 2018. He is currently the Associate Editor of Multimedia System, the editorial members of Frontiers of Information Technology & Electronic Engineering. He has won various honors such as the Award of National Science Fund for Distinguished Young Scholars of China (2016). His research interests mainly include Legal Intelligence, Multimedia Analysis and Retrieval and Machine Learning.-->
<!--          </p>-->
          <div class="card-actions">
            <div class="badge">Zhejiang University</div>
            <div class="badge little-margin-left">China</div>
          </div>
        </div>
      </div>
      <br>
      <h2 class="text-3xl font-black">STEERING COMMITEE</h2>
      <ul style="list-style-type:disc;padding-left: 20px">
        <li>Yating Zhang, Advanced NLP algorithm scientist, Alibaba DAMO Academy</li>
        <li>Xiaozhong Liu, Worcester Polytechnic Institute, Associate Professor at School of Informatics</li>
        <li>Changlong Sun, Senior NLP algorithm scientist, Alibaba DAMO Academy</li>
        <li>Fei Wu, Professor at School of Computer Science, Zhejiang University</li>
      </ul>
    </article>
  </div>
  <el-backtop :right="100" :bottom="100"/>
</template>

<script lang="ts">
import {defineComponent} from "vue";

export default defineComponent({
  setup() {
    const head = "The 2nd International Workshop on Legal Intelligence Held in conjunction with ICDM 2023（LegalAI@ICDM2023）"
    const news = " LegalAI@ICDM2023 is coming and calling for paper! "
    const proposal = "In the digital era, data mining, machine learning and NLP techniques are playing increasingly vital roles in legal domain. While the open datasets and innovative deep learning methodologies provide critical potentials, in the legal domain, efforts need to be made to transfer the theoretical/algorithmic models into the real applications to assist users, lawyers, judges and the legal professions to solve the real problems. Meanwhile, explainable AI has been investigated to generally help to facilitate the implementation of AI/ML in certain domains (e.g., medical domain), and specifically help to facilitate transparency and trust. However, the research on fairness is still blank in legal domain. Therefore, the objective of this workshop is to aggregate studies/applications of data mining/machine learning and NLP automation as well as fairness/explainable AI in the context of classical/novel legal tasks, which address algorithmic, data and social challenges of legal intelligence. Keynote and invited presentations from industry and academic will be able to fill the gap between ambition and execution in the legal domain.";
    return {
      head,
      news,
      proposal
    };
  },
  components:{

  },
  methods:{

  },
  data(){
    return({
      startTime:"",
      endTime:""
    })
  }
});
</script>

<style scoped>
.square{
  list-style-type:square;
  padding-left: 20px;
}
.circle{
  list-style-type:circle;
  padding-left: 20px;
}
.little-margin-left{
  margin-left: 5px;
}
.font-italic{
  font-style:italic;
}
</style>
