
<script>
    import {Icon} from '@steeze-ui/svelte-icon'
    import {ChartPie, ChevronUp, ClipboardList, Collection, DocumentReport} from "@steeze-ui/heroicons"
</script>

<aside class="flex-initial w-64 border-r border-gray-200" aria-label="Sidebar">
  <div class="overflow-y-auto rounded dark:bg-gray-800">
      <ul class="space-y-2 px-3 py-4">
          <li>
              <a href="#" class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
                <Icon src={ChartPie} theme='solid' class='w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white' />
                <span class="ml-3">Overview</span>
              </a>
          </li>
          <li>
              <a href="#" class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
                <Icon src={DocumentReport} theme='solid' class='w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white' />
                <span class="flex-1 ml-3 whitespace-nowrap">Versions</span>
                <span class="inline-flex justify-center items-center p-3 ml-3 w-3 h-3 text-sm font-medium text-blue-600 bg-blue-200 rounded-full dark:bg-blue-900 dark:text-blue-200">3</span>
              </a>
          </li>
        </ul>
        <div class="border-t"/>
        <ul class="space-y-2 px-3 py-4">
          <li>
              <a href="#" class="flex items-center p-2 text-base font-normal bg-gray-100 text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
                <Icon src={Collection} theme='solid' class='w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white' />
                <span class="flex-1 ml-3 whitespace-nowrap">Objects</span>
                <Icon src={ChevronUp} theme='solid' class='w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white' />
              </a>
              <ul class="ml-4">
                  <li>
                    <a href="#" class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
                        <Icon src={ClipboardList} theme='solid' class='w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white' />
                        <span class="flex-1 ml-3 whitespace-nowrap">Bounded context 1</span>
                    </a>
                  </li>
                  <li>
                    <a href="#" class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
                        <Icon src={ClipboardList} theme='solid' class='w-6 h-6 text-blue-500 transition duration-75 dark:text-blue-400 group-hover:text-blue-900 dark:group-hover:text-white' />
                        <span class="flex-1 ml-3 whitespace-nowrap">Bounded context 2</span>
                    </a>
                  </li>
              </ul>
          </li>
      </ul>
  </div>
</aside>