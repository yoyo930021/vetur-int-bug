<script lang="ts">
import __vlsComponent from "./HelloWorld.vue";
import { __vlsRenderHelper, __vlsComponentHelper, __vlsIterationHelper } from "vue-editor-bridge";
__vlsRenderHelper(__vlsComponent, function () { __vlsComponentHelper(this, "div", { props: {}, on: {}, directives: [] }, [__vlsIterationHelper(this.groups, (group) => __vlsComponentHelper(this, "ul", { props: { "key": group.id }, on: {}, directives: [] }, [__vlsComponentHelper(this, "li", { props: {}, on: {}, directives: [] }, [__vlsIterationHelper(group.list, (item) => __vlsComponentHelper(this, "ul", { props: { "key": item }, on: {}, directives: [] }, []))])]))]); });
</script>