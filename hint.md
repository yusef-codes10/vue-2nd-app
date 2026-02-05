# CDN Link
<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>

# Syntax/structure
const {createApp, ref} = Vue
createApp({
	setup() {
		//SET DATA HERE
		const VARIABLENAME = ref(VARIABLECONTENT)
		return {
		//RETURN DATA HERE
		}
	}
}).mount("#app")