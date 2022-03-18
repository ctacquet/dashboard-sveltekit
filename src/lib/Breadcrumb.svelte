<script>
    import {Icon} from '@steeze-ui/svelte-icon'
    import {ChevronRight, PresentationChartBar} from "@steeze-ui/heroicons"
</script>

<nav class="flex border-b p-4" aria-label="Breadcrumb">
    <ol class="inline-flex items-center space-x-1 md:space-x-3">
      <li class="inline-flex items-center">
        <a href="#" class="inline-flex items-center text-sm font-medium text-gray-700 hover:text-gray-900 dark:text-gray-400 dark:hover:text-white">
            <Icon src={PresentationChartBar} theme='solid' class='mr-2 w-5 h-5' />
            Projects
        </a>
      </li>
      <li>
        <div class="flex items-center">
            <Icon src={ChevronRight} theme='solid' class='w-6 h-6 text-gray-400' />
            <a href="#" class="ml-1 text-sm font-medium text-gray-700 hover:text-gray-900 md:ml-2 dark:text-gray-400 dark:hover:text-white">BookShelf</a>
        </div>
      </li>
      <li>
        <div class="flex items-center">
            <Icon src={ChevronRight} theme='solid' class='w-6 h-6 text-gray-400' />
            <a href="#" class="ml-1 text-sm font-medium text-gray-700 hover:text-gray-900 md:ml-2 dark:text-gray-400 dark:hover:text-white">v1.0</a>
        </div>
      </li>
      <li aria-current="page">
        <div class="flex items-center">
            <Icon src={ChevronRight} theme='solid' class='w-6 h-6 text-gray-400' />
            <span class="ml-1 text-sm font-medium text-gray-400 md:ml-2 dark:text-gray-500">Bounded context 1</span>
        </div>
      </li>
    </ol>
  </nav>