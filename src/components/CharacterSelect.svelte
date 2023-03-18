<div class="container w-full max-w-xs mx-auto my-6">
  <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4" method="POST">
    <div class="mb-4">
      <label class="block text-gray-700 text-sm font-bold mb-2" for="region">
        Region
      </label>
      <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="region" name="region" list="regions" required />
      <datalist id="regions">
        <option value="eu">Europe</option>
        <option value="us">United States</option>
        <option value="kr">Korea</option>
        <option value="tw">Taiwan</option>
      </datalist>
    </div>
    <div class="mb-4">
      <label class="block text-gray-700 text-sm font-bold mb-2" for="realm">
        Realm
      </label>
      <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 mb-3 leading-tight focus:outline-none focus:shadow-outline" id="realm" name="region" type="text" placeholder="Realm" required />
    </div>
    <div class="mb-6">
      <label class="block text-gray-700 text-sm font-bold mb-2" for="name">
        Character Name
      </label>
      <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 mb-3 leading-tight focus:outline-none focus:shadow-outline" id="name" name="name" type="text" placeholder="Character Name" required />
    </div>
    <div class="flex items-center justify-between">
      <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline">Go</button>
    </div>
  </form>
  <p class="text-center text-gray-500 text-xs">
    &copy;2023 Jamie Taylor All rights reserved.
  </p>
</div>