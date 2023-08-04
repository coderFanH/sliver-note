# 数组-pop/push，shift/unshift

<div class="flex justify-center">
  <carousel arrow draggable class="w-100 h-100">
    <div class="mt-20 flex flex-col justify-center">
      <div class="mb-5">数组的队列操作</div>
      <img src="/queue.png" class="rounded"/>
    </div>
    <div class="mt-20 flex flex-col justify-center">
      <div class="mb-5">数组的队列操作</div>
      <img src="/stack.png" class="rounded"/>
    </div>
  </carousel>

  ```js
  const arr = ['apple', 'banana', 'pear'];

  arr.push('fruits');
  console.log(arr);

  arr.shift('watermelon');
  console.log(arr);

  arr.unshift('watermelon');
  console.log(arr);

  arr.pop();
  console.log(arr);

  ```
</div>