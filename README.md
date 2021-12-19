<div id="my-lucky"></div>

<script src="https://cdn.jsdelivr.net/npm/lucky-canvas@1.7.7"></script>
<script>
  const myLucky = new LuckyCanvas.LuckyWheel('#my-lucky', {
    width: '200px',
    height: '200px',
    blocks: [{ padding: '10px', background: '#869cfa' }],
    prizes: [
      { fonts: [{ text: '谢谢惠顾' }], background: '#e9e8fe' },
      { fonts: [{ text: 'IPhone 13 Pro' }], background: '#b8c5f2' },
      { fonts: [{ text: '520红包' }], background: '#e9e8fe' },
      { fonts: [{ text: '么么哒一个' }], background: '#b8c5f2' },
      { fonts: [{ text: '口红一支' }], background: '#e9e8fe' },
      { fonts: [{ text: '香水一瓶' }], background: '#b8c5f2' },
      { fonts: [{ text: '清空购物车' }], background: '#b8c5f2' },
      { fonts: [{ text: '洗袜子一个月' }], background: '#b8c5f2' },
    ],
  })
</script>
