<script lang="ts">
  // import big from 'big.js';
  import Web3 from 'web3';
  import { abi as uniswap_pair } from '@uniswap/v2-core/build/IUniswapV2Pair.json';

  let web3ws: Web3 = new Web3(import.meta.env.VITE_WEB3_URL_WS);
  console.log(uniswap_pair);

  // let pair_contract = new web3ws.eth.Contract(
  //   uniswap_pair,
  //   import.meta.env.VITE_PAIR_ADDRESS
  // );
</script>

<main>
  <h1>Hello World</h1>
</main>
