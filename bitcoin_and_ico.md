* 전망
    * 2016 다보스 포럼 - 4차 산업 혁명
        * 빅데이터와 블록체인이 승자
    * 2015년 World Economic Forum - [Technology Tipping Points and Societal Impact](http://www3.weforum.org/docs/WEF_GAC15_Technological_Tipping_Points_report_2015.pdf)
        * `2023`: 정부가 처음으로 블록체인으로 세금을 걷을 것이다.
        * `2027`: 전세계 GDP의 10%가 블록체인 기술에 저장될 것이다.
            * (발표자의 개인 의견) 블록체인에 저장될 금액의 규모는 \$10 trillion 예상. 현재(2017년) 는 \$80 billion. 십년 이내에 125배 성장 예상
* 비트코인
    * 2008년: Satoshi Nakamoto가 발표한 논문 [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf)
    * 2009년: 비트코인 시스템 가동 시작
    * 2010년: Pizza Day. papa zones Pizza 2판을 10,000BTC에 판매 (현재가로 약 250억원)
        * [관련기사](http://www.coindesk.com/bitcoin-pizza-day-celebrating-pizza-bought-10000-btc/)
        * 언론을 타면서 가격 형성 시작 (\$0.1 / 1BTC)
    * 2013년: 거래 수단으로 비트코인을 사용하던 마약 거래 사이트 Silk Road가 FBI에 적발됨.
        * [관련기사](http://money.cnn.com/2013/11/27/technology/bitcoin-silk-road/)
        * 언론에 화제가 되면서 가격이 상승하기 시작 (\$1,000 / 1 BTC)
* 알트코인 (Alternative Coin)
    * 비트코인을 제외한 가상화폐
    * 2013년에 비트코인이 활성화된 이후에 많은 알트코인이 생겨남
    * Ethereum, Ripple, Litecoin, Dash
* 비트코인의 원리
    * 전세계 약 7,000~8,000개의 풀노드가 P2P로 연결되어 있다.
        * [비트코인 풀노드 현황](https://bitnodes.21.co/) 8,003 노드 (2017/07)
        * [이더리움 풀노드 현황](https://www.ethernodes.org/network/1) 25,152 노드 (2017/07)
    * 풀노드는 약 47만개의 블록을 모두 가지고 있다.
        * [비트코인 블록 현황](https://blockexplorer.com/) 476,478 블록 (2017/07)
        * [이더리움 블록 현황](https://ethstats.net/) 4,042,354 블록 (2017/07)
    * 특정 블록의 데이터를 변조하기 위해서는, 해당 블록을 포함한 이후의 모든 블록 데이터를 8,000개의 풀노드에서 한 번에 수정해야 한다. 즉, 해킹이 매우 어렵다.
    * 위와 같은 블록 체인은 이미 있었는데, `사토시`가 마지막 블록을 확정하는 문제를 해결하여 코인시스템을 만들 수 있게 되었다. 이 마지막 블록을 확정하는 문제가 바로 `비잔틴 장군의 문제`이다.
    * (블록체인에 대한 기초적인 기술을 간단히 언급하고 넘어감)
    * 마지막 블록을 확정한 노드에게 주는 혜택
        * 12.5 BTC (= 약 3~4천만원)
        * 해당 블록에서 생긴 거래 수수료를 모두 갖는다. (블록당 약 20만개 거래 x 100 사토시(₩2.6))
        * [거래 수수료](https://bitcoinfees.21.co/)
    * PoW 에서 PoS로 전환하는 추세
        * PoW는 속도가 느리다.
        * PoW는 에너지를 많이 소비한다.
        * PoS도 해킹에 대한 취약점이 존재한다.
* 이더리움
    * 2014년 Vitalik Buterin(당시 19세)가 White Paper를 발표하고, ICO로 \$17M 를 유치
        * [White Paper](https://github.com/ethereum/wiki/wiki/White-Paper)
        * [Yellow Paper](https://ethereum.github.io/yellowpaper/paper.pdf)
    * 2015년에 이더리움 가동 시작
    * 현재 가치는 \$21 billion으로 약 1,000배 가까이 상승. ICO의 대표적인 성공 사례.
        * [이더리움 현재 가치](https://etherscan.io/stat/supply) $21,152,193,410 (2017/07)
    * 이더리움은 비트코인에 스마트 컨트랙트가 추가되었다.
    * 법률도 code이고, 컴퓨터 프로그램도 code이다. 모두 강제성이 있다. 국가의 법률보다 컴퓨터 프로그램(법)이 강제성이 더 크다. `이더리움의 핵심 가치`.
    * 스마트 컨트랙트를 활용한 수많은 DApp들이 생겨났다.
        * [DApp 목록](https://dapps.ethercasts.com/)
    * 탈중앙화된 서비스(DApp)는 수수료를 낮게 만들 수 있다. (ex. 탈중앙화된 우버). 스마트 컨트랙트는 이러한 서비스의 근간.
        * *탈중앙화된 앱에 대해 자세한 조사를 해보자*
* 실습
    * Mycelium을 설치하고, 비트코인 송수신을 한다.

* Blockchain OS (BOS)
    * DApp의 플랫폼(OS)
* 블록체인은 차세대 인터넷 기술
    * 현재는 정보의 인터넷, 향후에는 가치의 인터넷
    * 주식 거래: 거래 당사자는 사본을 가지고 있고, 원본 장부는 증권예탁원과 금융결제원에 있다. 주식 매도에 3일이 걸리는 이유는 여러 공인 기간 (민간 TTP:Trusted Third Party, 공공 TTP) 간에 주식 이동이 일어나기 때문에
    * 반면 블록체인은 `소유권 원본`을 거래한다.
    * 기존 시스템에 대한 비유: [Goldberg Machine: 간단한 작업을 복잡하게 해결하는 사람을 풍자](https://s-media-cache-ak0.pinimg.com/736x/1e/2a/a2/1e2aa21c9241c702db548c9b078c9f53--rube-goldberg-machine-project-based-learning.jpg)
    * 기존에는 복사본을 원본 대접하면서 처리했지만, 블록 체인을 이용하면 원본을 상대방과 내가 직접 거래할 수 있다.
        * 스웨덴: 블록체인 기반의 토지거래 시스템 시범 운영. [chromaway](http://chromaway.com/landregistry/)
* Industry 4.0
    * 많은 수의 IoT 기기
    * IoT 기기의 센서로부터 어마어마한 양의 데이터가 나온다
    * Big Data 처리 필요
    * 인간이 모두 처리할 수 없다. Machine-to-Machine Communication이 필요하다.
    * 기계와 기계의 소통에 스마트 컨트랙트가 사용된다. 거래에는 가상화폐가 사용된다. 또 IoT 보안 문제를 해결할 수 있다.(근거에 대한 설명은 없음)
* Govern-tech (by 박창기)
    * Governance와 Technology의 합성어
    * 블록체인을 이용하여 많은 공공서비스를 공인 기관(정부, 은행)을 거치지 않고 민간 영역에서 제공하는 것
    * 사례
        * r3의 Corda
            * [프로젝트 홈](https://www.corda.net/)
            * 전세계 100대 은행 중 70개 은행이 블록 체인을 이용한 공동 청산 시스템 개발 (SWIFT 대체)
            * 은행/보험/카드/증권등의 금융 시스템에서 1년에 80조 소요 => 40조로 낮출 수 있다.
        * IBM: Hyper Ledger
            * [프로젝트 홈](https://www.ibm.com/blockchain/hyperledger.html)
        * Digital Asset Holdings
            * [프로젝트 홈](https://digitalasset.com/)
            * 호주의 증권시스템을 블록체인으로 바꾸고 있다.
    * Fiat Currency(법정화폐)를 블록체인으로 변경
        * 영국, 스웨덴, 카나다, 러시아, 우크라이나, 호주, 중국, 싱가포르 등의 국가에서 블록체인으로 변경하는 것을 시험 중
        * 지하 경제가 사라진다.
        * 각 은행의 전산시스템이 단일화된다.
*  ICO
    * (ICO 연혁 설명)
    * 모럴 해저드
        * 글로벌 시장에서 돈이 아닌 비트코인으로 투자 받았기 때문에, 각국 정부가 규제할 수 없다.
        * 자율적인 규제가 중요하지만, 동작하지 않는다.
    * 규제 회피
        * ICO 대신 Token Generation Event, Donation/Fundraising 라고 표현한다.
        * 재단법인을 Swiss, Singapore, Estonia에 세운다.
    * VC -> ICO
        * 과거에는 소수 엘리트(VC)만 투자가 가능했지만, ICO로는 누구나 투자가 가능하다.
    * ICO의 진위 판별법
        * 다단계와 연결된 것은 무조건 가짜
        * White Paper가 글로벌하게 쓰여져 있는가?
        * Key Person이 누구냐? 엔지니어/마켓팅 팀이 제대로 구성되어 있는가?
        * 기술적인 진보가 확실히 있는가?
        * Global Marketing 능력이 있는가?
        * Fundraising Schedule이 잘 설계되어 있느냐?
        * 이런 내용이 잘 되어 있는 ICO에는 투자!
